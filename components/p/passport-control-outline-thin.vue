<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="h3kp1aciy"/><path class="cbc39pbyz"/><path class="yuybrcb9z"/><path class="t9co17b-n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:passport-control-outline-thin" /></template>
<style>
.cbc39pbyz {
  d: path("M8 6v15");
}

.h3kp1aciy {
  d: path("M4 8a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2v11a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.t9co17b-n {
  d: path("M9.5 21a4.5 4.5 0 0 1 9 0");
}

.yuybrcb9z {
  d: path("M12 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
