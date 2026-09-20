<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="cacmi2bmi"/><path class="jtt8g10_o"/><path class="ikiprn9sq"/><path class="g31q_jb0h"/><path class="zrsj1cc7l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:mcp-resource-template-outline-regular" /></template>
<style>
.cacmi2bmi {
  d: path("M13 3H9L6 6v15h12V8");
}

.g31q_jb0h {
  d: path("M9 10v4");
}

.ikiprn9sq {
  d: path("M9 14h6");
}

.jtt8g10_o {
  d: path("M9 10h6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.zrsj1cc7l {
  d: path("M15 10v4");
}

</style>
