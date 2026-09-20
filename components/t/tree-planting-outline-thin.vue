<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="km-udeb-c"/><path class="m9qgpk56l"/><path class="jr__k4bcu"/><path class="bt921xbxy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:tree-planting-outline-thin" /></template>
<style>
.bt921xbxy {
  d: path("M5 21a7 7 0 0 1 14 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jr__k4bcu {
  d: path("M12 12c0 -4 3 -6 7 -6 0 4 -3 6 -7 6");
}

.km-udeb-c {
  d: path("M12 17V9");
}

.m9qgpk56l {
  d: path("M12 9c0 -4 -3 -6 -7 -6 0 4 3 6 7 6");
}

</style>
