<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="r6d8msbmx"/><path clip-rule="evenodd" class="qrc-mgazh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:piano-sharp-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.qrc-mgazh {
  fill-rule: evenodd;
  d: path("M17.988 21H14.012C14.559 20.994 15 20.548 15 20V14C15 13.448 14.552 13 14 13V5H18V13C17.448 13 17 13.448 17 14V20C17 20.548 17.441 20.994 17.988 21ZM9.988 21H6.012C6.559 20.994 7 20.548 7 20V14C7 13.448 6.552 13 6 13V5H10V13C9.448 13 9 13.448 9 14V20C9 20.548 9.441 20.994 9.988 21Z");
}

.r6d8msbmx {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 3H22C22.552 3 23 3.448 23 4V20C23 20.552 22.552 21 22 21H2C1.448 21 1 20.552 1 20V4C1 3.448 1.448 3 2 3H12Z");
}

</style>
