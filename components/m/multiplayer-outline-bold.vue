<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="mdqmuqzrh"/><path class="rp7ii8bgy"/><path class="fim5wvb3d"/><path class="lhhiiffss"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:multiplayer-outline-bold" /></template>
<style>
.fim5wvb3d {
  d: path("M5.5 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.lhhiiffss {
  d: path("M16.5 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.mdqmuqzrh {
  d: path("M3 8v8h7V8Z");
}

.rp7ii8bgy {
  d: path("M14 8v8h7V8Z");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
