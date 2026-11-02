<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="tw7y6mbhw"/><path class="o4qyerm4y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:volume-close-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.o4qyerm4y {
  d: path("M15.707 8.293L18 10.586l2.293-2.293a.999.999 0 1 1 1.414 1.414L19.414 12l2.293 2.293a.999.999 0 1 1-1.414 1.414L18 13.414l-2.293 2.293a.999.999 0 1 1-1.414-1.414L16.586 12l-2.293-2.293a.999.999 0 1 1 1.414-1.414");
}

.tw7y6mbhw {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 4v16a1.002 1.002 0 0 1-1.707.707L6.586 17H3a1 1 0 0 1-1-1V8a1 1 0 0 1 1-1h3.586l3.707-3.707A1 1 0 0 1 12 4");
}

</style>
