<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hjjgjfl_f"/><path class="kdt2ovb0a"/><path class="vsy5fvbnx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:manager-feedback" /></template>
<style>
.hjjgjfl_f {
  d: path("M4 5a2.5 2.5 0 0 1 2.5-2.5h11A2.5 2.5 0 0 1 20 5v9.5a2.5 2.5 0 0 1-2.5 2.5h-3L12 20.5L9.5 17h-3A2.5 2.5 0 0 1 4 14.5Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kdt2ovb0a {
  d: path("M11.781 5.25h.438a.805.805 0 0 1 .781 1l-.068.272A.96.96 0 0 1 12 7.25a.96.96 0 0 1-.932-.728L11 6.25a.805.805 0 0 1 .781-1");
}

.vsy5fvbnx {
  d: path("M12 7.25za.906.906 0 0 1 .89.737l.711 3.733a1.5 1.5 0 0 1-.412 1.341l-.314.314a1.237 1.237 0 0 1-1.75 0l-.314-.314a1.5 1.5 0 0 1-.412-1.341l.711-3.733A.906.906 0 0 1 12 7.25");
}

</style>
