<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="j9schwodo"/><path class="dbb3ymiyd"/><path class="gcalxb98a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:vaccine-outline-bold" /></template>
<style>
.dbb3ymiyd {
  d: path("M9 7V4h6v3");
}

.gcalxb98a {
  d: path("M8 13h8");
}

.j9schwodo {
  d: path("M8 7v13h8V7Z");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
