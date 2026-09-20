<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="xekk022fw"/><path class="jnf_2db5t"/><path class="gl3o38_gx"/><path class="z8c0a6b1x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:pregnancy-scan-outline-regular" /></template>
<style>
.gl3o38_gx {
  d: path("M8 21h8");
}

.jnf_2db5t {
  d: path("M12 18v3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.xekk022fw {
  d: path("M3 6a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v10a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

.z8c0a6b1x {
  d: path("M9 13a4 4 0 0 1 6 -5c0 4 -2 6 -6 5");
}

</style>
