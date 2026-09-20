<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="kuk8yacoy"/><path class="n8h0kccut"/><path class="if5ft31dv"/><path class="mdci-mi7f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:topic-outline-regular" /></template>
<style>
.if5ft31dv {
  d: path("M11 19a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.kuk8yacoy {
  d: path("M8 10a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

.mdci-mi7f {
  d: path("M18 18a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.n8h0kccut {
  d: path("M4 18a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
