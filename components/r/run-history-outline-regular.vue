<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="d5czi6rdr"/><path class="l-z02yb4d"/><path class="wluwrgbwr"/><path class="ul0m4fbfe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:run-history-outline-regular" /></template>
<style>
.d5czi6rdr {
  d: path("M3 4a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v16a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

.l-z02yb4d {
  d: path("M11 5v5l2.5 -2.5Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ul0m4fbfe {
  d: path("M9 17.5h6");
}

.wluwrgbwr {
  d: path("M9 14.5h6");
}

</style>
