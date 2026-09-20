<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="am6m0sb5o"/><path class="nkayykbew"/><path class="jnvfxxwun"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:meteor-outline-bold" /></template>
<style>
.am6m0sb5o {
  d: path("M16 4.5 19.5 8 16 11.5 12.5 8Z");
}

.jnvfxxwun {
  d: path("m7 21 5 -5");
}

.nkayykbew {
  d: path("m3 19 7 -7");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
