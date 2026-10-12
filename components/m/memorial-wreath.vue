<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t0uttbcgj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:memorial-wreath" /></template>
<style>
.t0uttbcgj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.27 15.03q-1.42-3.12-4.31-1.27q1.42 3.12 4.31 1.27m-2.52-3.84Q8.3 8.13 5.06 7.03q-1.55 3.05 1.69 4.16m1.44-4.36q3.36-.7 2.2-3.92q-3.36.69-2.2 3.92m4.3-1.6q2.64 2.19 4.44-.72q-2.64-2.19-4.44.72m3.93 2.37q-.06 3.43 3.34 3.02q.07-3.43-3.34-3.02m.61 4.55q-2.73 2.09-.28 4.49q2.72-2.08.28-4.49M12 17.25c-1-1.25-2.75-1.25-2.75 0s1.75 1.25 2.75 0c1 1.25 2.75 1.25 2.75 0S13 16 12 17.25l-1.5 4m1.5-4l1.5 4");
}

</style>
