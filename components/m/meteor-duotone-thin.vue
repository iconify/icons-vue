<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="aoul07b2h"/><path class="am6m0sb5o"/><path class="nkayykbew"/><path class="jnvfxxwun"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:meteor-duotone-thin" /></template>
<style>
.am6m0sb5o {
  d: path("M16 4.5 19.5 8 16 11.5 12.5 8Z");
}

.aoul07b2h {
  fill: currentColor;
  d: path("M16 4.5 19.5 8 16 11.5 12.5 8Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jnvfxxwun {
  d: path("m7 21 5 -5");
}

.nkayykbew {
  d: path("m3 19 7 -7");
}

</style>
