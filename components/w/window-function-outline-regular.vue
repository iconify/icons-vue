<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ou9p_ybmc"/><path class="k9n1nabge"/><path class="m45ql5bta"/><path class="s1n7yd_mp"/><path class="s92gxib6y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:window-function-outline-regular" /></template>
<style>
.k9n1nabge {
  d: path("M3 10h12.5");
}

.m45ql5bta {
  d: path("M3 16h12.5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ou9p_ybmc {
  d: path("M3 4h12.5");
}

.s1n7yd_mp {
  d: path("M3 22h12.5");
}

.s92gxib6y {
  d: path("M18.5 7H21v12h-2.5");
}

</style>
