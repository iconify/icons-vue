<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="kds04kq-i"/><path class="y5840vb_h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:triangle-minus-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.kds04kq-i {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m14.986 5.675l5.5 9A3.499 3.499 0 0 1 17.5 20h-11a3.499 3.499 0 0 1-2.986-5.325l5.5-9a3.5 3.5 0 0 1 5.972 0");
}

.y5840vb_h {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m14.986 5.675l5.5 9C21.912 17.007 20.233 20 17.5 20h-11c-2.733 0-4.412-2.993-2.986-5.325l5.5-9c1.364-2.233 4.608-2.233 5.972 0M10 14h4");
}

</style>
