<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nkh2lf_rr"/><path class="s77-87bru"/><path class="vefub-1rj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ukraine-tryzub" /></template>
<style>
.nkh2lf_rr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 35.03H12.955V9.132c4.982 2.98 5.173 10.99 5.713 15.197a2.86 2.86 0 0 0-2.455 2.833c0 1.58 1.03 2.672 2.86 3.02c2.599.492 4.927.746 4.927 4.846m-7.787-7.865h-3.258");
}

.s77-87bru {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 43.5c0-1.764 4.418-3.29 4.418-9.25c0-4.624-4.418-8.605-4.418-13.778C24 12.915 26.174 7.79 24 4.5c-2.174 3.29 0 8.415 0 15.972c0 5.173-4.418 9.154-4.418 13.779c0 5.96 4.418 7.485 4.418 9.249");
}

.vefub-1rj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 35.03h11.045V9.132c-4.982 2.98-5.173 10.99-5.713 15.197a2.86 2.86 0 0 1 2.455 2.833c0 1.58-1.03 2.672-2.86 3.02c-2.599.492-4.927.746-4.927 4.846m7.787-7.865h3.258M24 35.029V43.5");
}

</style>
