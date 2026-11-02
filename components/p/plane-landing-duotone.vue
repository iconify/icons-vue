<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="b8aqlhi_q"/><path class="p-3aw-slw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:plane-landing-duotone" /></template>
<style>
.b8aqlhi_q {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m13.293 15.707l-1.636-1.636l-4.985.831a2 2 0 0 1-1.743-.559l-.136-.136a1.614 1.614 0 0 1 .173-2.431l2.766-2.075L7.382 9h-.968A2 2 0 0 1 5 8.414l-.207-.207a1.706 1.706 0 0 1 0-2.414l3-3a1.706 1.706 0 0 1 2.414 0l.207.207A2 2 0 0 1 11 4.414v.968l.701.35l2.075-2.766a1.615 1.615 0 0 1 2.431-.173l.136.136a2 2 0 0 1 .559 1.743l-.831 4.985l1.636 1.636c1.536 1.536 2.951 3.462 1 5.414c-.692.692-1.538 1.096-2.528.899c-1.102-.221-2.116-1.128-2.886-1.899");
}

.ft5dv1b6b {
  fill: none;
}

.p-3aw-slw {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m17 12l-2-2l.915-5.492a1 1 0 0 0-.279-.872L15.5 3.5a.613.613 0 0 0-.924.066L12 7l-2-1V4.414a1 1 0 0 0-.293-.707L9.5 3.5a.707.707 0 0 0-1 0l-3 3a.707.707 0 0 0 0 1l.207.207A1 1 0 0 0 6.414 8H8l1 2l-3.434 2.576a.613.613 0 0 0-.066.924l.136.136a1 1 0 0 0 .872.28L12 13l2 2c2 2 3 2 4 1s1-2-1-4M3 21h18");
}

</style>
