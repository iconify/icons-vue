<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mbv9wkn3i"/><path class="j9schwodo"/><path class="dbb3ymiyd"/><path class="gcalxb98a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:vaccine-duotone-thin" /></template>
<style>
.dbb3ymiyd {
  d: path("M9 7V4h6v3");
}

.gcalxb98a {
  d: path("M8 13h8");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j9schwodo {
  d: path("M8 7v13h8V7Z");
}

.mbv9wkn3i {
  fill: currentColor;
  d: path("M8 7v13h8V7Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
