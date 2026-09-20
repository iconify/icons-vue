<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="o1sdh65rz"/><path class="rrzohjbez"/><path class="jexvsc_6c"/><path class="ap8lrtbka"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:minify-outline-bold" /></template>
<style>
.ap8lrtbka {
  d: path("M8 20.25a1.75 1.75 0 0 1 1.75 -1.75h4.5A1.75 1.75 0 0 1 16 20.25 1.75 1.75 0 0 1 14.25 22h-4.5A1.75 1.75 0 0 1 8 20.25");
}

.jexvsc_6c {
  d: path("m10 14 2 2 2 -2");
}

.o1sdh65rz {
  d: path("M4 4a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2v4a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
}

.rrzohjbez {
  d: path("M12 12v3");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
