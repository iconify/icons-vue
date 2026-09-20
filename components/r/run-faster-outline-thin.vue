<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="d5czi6rdr"/><path class="l-z02yb4d"/><path class="l3jp1qxjq"/><path class="gbpohbcrz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:run-faster-outline-thin" /></template>
<style>
.d5czi6rdr {
  d: path("M3 4a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v16a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

.gbpohbcrz {
  d: path("M12.5 13.5 15 16l-2.5 2.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l-z02yb4d {
  d: path("M11 5v5l2.5 -2.5Z");
}

.l3jp1qxjq {
  d: path("M9.5 13.5 12 16l-2.5 2.5");
}

</style>
