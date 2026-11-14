<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="f88g7tb8e"/><path class="nqckfjm9x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:robot-vacuum-room-select" /></template>
<style>
.f88g7tb8e {
  fill: currentColor;
  d: path("M9.5 5H5a2 2 0 0 0-2 2v10a2 2 0 0 0 2 2h4.5Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nqckfjm9x {
  d: path("M9.5 5H19q.098 0 .196.01q.098.009.194.028q.097.02.191.048q.094.029.184.066q.091.038.178.084q.086.046.168.101t.158.117t.145.132q.07.069.132.145t.117.158t.101.168q.046.087.084.178q.037.09.066.184q.028.094.048.191q.019.096.028.194T21 7v5.972M12.157 19H9.5m5.25-1l2 2L21 15.75");
}

</style>
