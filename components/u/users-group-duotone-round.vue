<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="g1-12mbjr"/><path class="a_rc_bytf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:users-group-duotone-round" /></template>
<style>
.a_rc_bytf {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 10a3 3 0 1 0 6 0a3 3 0 0 0-6 0M7 21c0-2.21 2.239-4 5-4s5 1.79 5 4M8 5a2.236 2.236 0 1 0-2 4m10-4a2.236 2.236 0 1 1 2 4M3 17c0-1.657 1.79-3 4-3m10 0c2.21 0 4 1.343 4 3");
}

.ft5dv1b6b {
  fill: none;
}

.g1-12mbjr {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M9 10a3 3 0 1 1 6 0a3 3 0 0 1-6 0M7 21c0-2.209 2.239-4 5-4s5 1.791 5 4Z");
}

</style>
