<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="h7g95-rcq"/><path class="u1loq0b-h"/><path class="scvfr3yen"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:town" /></template>
<style>
.h7g95-rcq {
  d: path("m2.89 8.571l3.5-3.85a1.5 1.5 0 0 1 2.22 0l3.5 3.85a1.5 1.5 0 0 1 .39 1.009V20a1.5 1.5 0 0 1-1.5 1.5H4A1.5 1.5 0 0 1 2.5 20V9.58a1.5 1.5 0 0 1 .39-1.009");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.scvfr3yen {
  d: path("M15.5 21.5v-4h3v4");
}

.u1loq0b-h {
  d: path("M12.5 13L17 8.5l4.5 4.5v8.5h-9m-5-9.5zA1.5 1.5 0 0 1 9 13.5A1.5 1.5 0 0 1 7.5 15A1.5 1.5 0 0 1 6 13.5A1.5 1.5 0 0 1 7.5 12");
}

</style>
