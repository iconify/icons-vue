<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="fp0jerb6p"/><path class="tqfrzx00u"/><path class="riix_db4t"/><path class="jbiy0-3tw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:video-summarise-outline-bold" /></template>
<style>
.fp0jerb6p {
  d: path("M10.5 6H13a3 3 0 0 1 3 3v6a3 3 0 0 1 -3 3H5a3 3 0 0 1 -3 -3V9a3 3 0 0 1 3 -3h2.5");
}

.jbiy0-3tw {
  d: path("M5 14h5");
}

.riix_db4t {
  d: path("M5 10h8");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.tqfrzx00u {
  d: path("m19 10 3 -3v10l-3 -3Z");
}

</style>
