<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gkj6vbuly"/><path class="s-qvifbka"/><path class="h0lf65bzj"/><path class="gr0pfvalr"/><path class="mhnr27bap"/><path class="uj789o2td"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:timetable-outline-thin" /></template>
<style>
.gkj6vbuly {
  d: path("M2 5a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v10a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

.gr0pfvalr {
  d: path("M9 10a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.h0lf65bzj {
  d: path("M17 21v-4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mhnr27bap {
  d: path("M12 7v3");
}

.s-qvifbka {
  d: path("M7 21v-4");
}

.uj789o2td {
  d: path("M12 10h2.5");
}

</style>
