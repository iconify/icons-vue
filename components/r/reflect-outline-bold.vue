<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="h2-2dgnfu"/><path class="hzsvawc8s"/><path class="u8aszkb6i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:reflect-outline-bold" /></template>
<style>
.h2-2dgnfu {
  d: path("M12 3v18");
}

.hzsvawc8s {
  d: path("m8 8 -4 4 4 4");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.u8aszkb6i {
  d: path("m16 8 4 4 -4 4");
}

</style>
