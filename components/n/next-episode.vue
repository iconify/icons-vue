<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="f_qopvbhh"/><path class="v_zfkl74m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:next-episode" /></template>
<style>
.f_qopvbhh {
  d: path("M6 3.5h12A3.5 3.5 0 0 1 21.5 7v6.5A3.5 3.5 0 0 1 18 17H6a3.5 3.5 0 0 1-3.5-3.5V7A3.5 3.5 0 0 1 6 3.5m2 17h8");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v_zfkl74m {
  d: path("m10.817 8.506l.748.486a1.5 1.5 0 0 1 0 2.516l-.748.486A1.5 1.5 0 0 1 8.5 10.736v-.972a1.5 1.5 0 0 1 2.317-1.258M16 7v6.5");
}

</style>
