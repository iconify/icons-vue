<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="br4_5duwz"/><path class="iexlgo4zk"/><path class="wprdp0m6y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:playback-speed-line-duotone" /></template>
<style>
.br4_5duwz {
  d: path("M12 22C17.5228 22 22 17.5228 22 12C22 6.47715 17.5228 2 12 2");
}

.iexlgo4zk {
  d: path("M12 22C11.2348 22 10.4897 21.9141 9.77378 21.7513M12.5 2C11.7273 2 10.9652 2.08764 10.226 2.25353M6.67906 20.4684C5.40892 19.6687 4.33134 18.5911 3.5316 17.3209M2.2487 14.2262C2.08594 13.5103 2 12.7652 2 12C2 11.2196 2.09939 10.46 2.28566 9.73101M3.71378 6.62301C4.57833 5.3737 5.72466 4.31359 7.04653 3.52495");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wprdp0m6y {
  d: path("M9 9.21316L9 14.7868C9 15.7105 9.93371 16.2944 10.6935 15.8458L15.4137 13.059C16.1954 12.5974 16.1954 11.4026 15.4137 10.941L10.6935 8.15419C9.93371 7.70561 9 8.28947 9 9.21316Z");
}

</style>
