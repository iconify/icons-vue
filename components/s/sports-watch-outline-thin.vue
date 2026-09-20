<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="meu59i09i"/><path class="pn1t5dbod"/><path class="jg-vwzb3v"/><path class="x1_r36phd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:sports-watch-outline-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jg-vwzb3v {
  d: path("M9 17v4h6v-4");
}

.meu59i09i {
  d: path("M6 9a2 2 0 0 1 2 -2h8a2 2 0 0 1 2 2v6a2 2 0 0 1 -2 2H8a2 2 0 0 1 -2 -2Z");
}

.pn1t5dbod {
  d: path("M9 7V3h6v4");
}

.x1_r36phd {
  d: path("M9 12h6");
}

</style>
