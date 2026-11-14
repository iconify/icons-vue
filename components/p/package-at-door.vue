<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ooxztxw5f"/><path class="md8qwoakp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:package-at-door" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.md8qwoakp {
  d: path("M13.75 14h4.5A1.75 1.75 0 0 1 20 15.75v4a1.75 1.75 0 0 1-1.75 1.75h-4.5A1.75 1.75 0 0 1 12 19.75v-4A1.75 1.75 0 0 1 13.75 14M16 14v3m-6-5.5h.01");
}

.ooxztxw5f {
  d: path("M7 21.5v-18a1 1 0 0 1 1-1h8a1 1 0 0 1 1 1V11M3 21.5h18");
}

</style>
