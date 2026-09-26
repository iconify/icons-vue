<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="g7gekvbgt"/><path class="qwgg3xbzh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:map-pin-heart-duotone" /></template>
<style>
.g7gekvbgt {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M18.7082 16L12.7454 22.6667C12.5556 22.8788 12.2846 23 12 23C11.7154 23 11.4444 22.8788 11.2546 22.6667L5.2918 16C3.8159 14.3499 3 12.2138 3 10C3 5.0294 7.0294 1 12 1C16.9706 1 21 5.0294 21 10C21 12.2138 20.1841 14.3499 18.7082 16Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qwgg3xbzh {
  d: path("M12 14.841C10.1796 13.2862 8.01 11.9483 8.01 9.9533C8.01 8.6861 9.0818 7.659 10.404 7.659C11.0025 7.659 11.5382 7.8768 12 8.2575C12.4618 7.8768 12.9975 7.659 13.596 7.659C14.9182 7.659 15.99 8.6861 15.99 9.9533C15.99 11.9483 13.8204 13.2862 12 14.841Z");
}

</style>
