<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="dwnj8ebpv"/><path class="kkard_6ho"/><path class="lm2p_gfvh"/><path class="j6kp_yter"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:watering-can-outline-bold" /></template>
<style>
.dwnj8ebpv {
  d: path("M6 10v10h10V10Z");
}

.j6kp_yter {
  d: path("M8 10c0 -4 6 -4 6 0");
}

.kkard_6ho {
  d: path("m16 12 5 -5");
}

.lm2p_gfvh {
  d: path("m19 5 3 3");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
