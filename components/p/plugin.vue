<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pko5kmbow"/><path class="b6pi5ilsw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:plugin" /></template>
<style>
.b6pi5ilsw {
  d: path("M6 8h2.5a2.25 2.25 0 1 1 3 0H14v2.75a2.25 2.25 0 1 1 0 3v3.75H6Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pko5kmbow {
  d: path("M2.5 13v6A2.5 2.5 0 0 0 5 21.5h14a2.5 2.5 0 0 0 2.5-2.5v-6");
}

</style>
