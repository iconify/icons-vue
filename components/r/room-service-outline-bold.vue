<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ils7yp4cg"/><path class="bv1y61bvs"/><path class="us2evabuy"/><path class="qw7b_6b1t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:room-service-outline-bold" /></template>
<style>
.bv1y61bvs {
  d: path("M4 16a8 8 0 0 1 16 0");
}

.ils7yp4cg {
  d: path("M2 16h20");
}

.qw7b_6b1t {
  d: path("M8 20h8");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.us2evabuy {
  d: path("M12 5.5V8");
}

</style>
