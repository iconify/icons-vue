<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="l2kewe7tu"/><circle class="q72b48b9q"/><path class="q2mrbpbpj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:master-key" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l2kewe7tu {
  d: path("M4 7.9V4.35q0-.35.26-.12l1.48 1.29q.26.23.45-.06l1.12-1.67q.19-.29.38 0l1.12 1.67q.19.29.45.06l1.48-1.29Q11 4 11 4.35V7.9q0 .35-.35.35h-6.3Q4 8.25 4 7.9");
}

.q2mrbpbpj {
  d: path("M12 15.75h9.25V19m-3.5-3.25v2.5");
}

.q72b48b9q {
  cx: 7.5px;
  cy: 15.75px;
  r: 4.5px;
}

</style>
