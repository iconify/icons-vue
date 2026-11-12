<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="j8004cbeu"/><path class="lywq3ibco"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:shuffle-line-duotone" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j8004cbeu {
  d: path("M2 17H5.60286C7.26213 17 8.09177 17 8.77953 16.6106C9.46728 16.2212 9.89413 15.5098 10.7478 14.087L13.2522 9.91303C14.1059 8.49021 14.5327 7.7788 15.2205 7.3894C15.9082 7 16.7379 7 18.3971 7H22M20 5L22 7L20 9");
}

.lywq3ibco {
  d: path("M2 7H5.60286C7.26213 7 8.09177 7 8.77953 7.3894C9.46728 7.7788 9.89413 8.49021 10.7478 9.91303L13.2522 14.087C14.1059 15.5098 14.5327 16.2212 15.2205 16.6106C15.9082 17 16.7379 17 18.3971 17H22M20 19L22 17L20 15");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
