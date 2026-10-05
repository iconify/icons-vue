<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="nie_nqh5q"/><path class="r-5ea2bpl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:video-2-sharp-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.nie_nqh5q {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M17 5C17.5523 5 18 5.44772 18 6V18C18 18.5523 17.5523 19 17 19H2C1.44772 19 1 18.5523 1 18V6C1 5.44772 1.44772 5 2 5H17Z");
}

.r-5ea2bpl {
  d: path("M21.5527 6.60544C21.8626 6.45049 22.2306 6.46731 22.5254 6.64939C22.8202 6.8316 23 7.1534 23 7.49997V16.5C23 16.8465 22.8202 17.1684 22.5254 17.3506C22.2306 17.5326 21.8626 17.5495 21.5527 17.3945L16.5527 14.8945C16.214 14.7251 16 14.3787 16 14V9.99997C16 9.62121 16.214 9.27484 16.5527 9.10544L21.5527 6.60544Z");
}

</style>
