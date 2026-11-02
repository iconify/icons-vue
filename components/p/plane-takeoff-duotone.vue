<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ku3ebov2i"/><path class="ucm_lmb3m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:plane-takeoff-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.ku3ebov2i {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m16.071 10.343l.831 4.985a2 2 0 0 1-.559 1.743l-.136.136a1.614 1.614 0 0 1-2.431-.173l-2.075-2.766l-.701.35v.968A2 2 0 0 1 10.414 17l-.207.207a1.706 1.706 0 0 1-2.414 0l-3-3a1.706 1.706 0 0 1 0-2.414L5 11.586A2 2 0 0 1 6.414 11h.968l.35-.701l-2.766-2.075a1.615 1.615 0 0 1-.173-2.431l.136-.136a2 2 0 0 1 1.743-.559l4.985.831l1.636-1.636c.77-.771 1.784-1.678 2.886-1.899c.99-.197 1.836.207 2.528.899c1.951 1.952.536 3.878-1 5.414Z");
}

.ucm_lmb3m {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m17 8l-2 2l.915 5.492a1 1 0 0 1-.279.872l-.136.136a.613.613 0 0 1-.924-.066L12 13l-2 1v1.586a1 1 0 0 1-.293.707L9.5 16.5a.707.707 0 0 1-1 0l-3-3a.707.707 0 0 1 0-1l.207-.207A1 1 0 0 1 6.414 12H8l1-2l-3.434-2.576A.613.613 0 0 1 5.5 6.5l.136-.136a1 1 0 0 1 .872-.28L12 7l2-2c2-2 3-2 4-1s1 2-1 4M3 21h18");
}

</style>
