<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="aj1uncbqw"/><path class="mddrthmzf"/><path class="nr6agbx1r"/><path class="yo0q-4dzc"/><path class="uc661cbro"/><path class="yafg6v4zg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:neighbour-person-outline-bold" /></template>
<style>
.aj1uncbqw {
  d: path("M4 7a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.mddrthmzf {
  d: path("M3 16a4 4 0 0 1 8 0");
}

.nr6agbx1r {
  d: path("M15 6v14");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.uc661cbro {
  d: path("M15 10h4");
}

.yafg6v4zg {
  d: path("M15 15h4");
}

.yo0q-4dzc {
  d: path("M19 6v14");
}

</style>
