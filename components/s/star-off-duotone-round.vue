<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="guf4bmb3u"/><path class="t-rd4ac6w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:star-off-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.guf4bmb3u {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m18.5 13.5l-7.833-7.833L12 3l3 6l7 1ZM18 21l-6-3l-6 3l1-6l-5-5l6.125-.875L17.6 18.6Z");
}

.t-rd4ac6w {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m11 5l1-2l3 6l7 1l-3 3m-1.4 5.6L18 21l-6-3l-6 3l1-6l-5-5l6.125-.875M2 3l19 19");
}

</style>
