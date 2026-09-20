<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="k2jzr9u7f"/><path class="uyba0j-4z"/><path class="wuegxr5di"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:subagent-outline-regular" /></template>
<style>
.k2jzr9u7f {
  d: path("M5 7a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.uyba0j-4z {
  d: path("M13 15a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.wuegxr5di {
  d: path("m10 9 4 4");
}

</style>
