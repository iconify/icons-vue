<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="cacmi2bmi"/><path class="pt-3kkb2k"/><path class="eqk2m_q5d"/><path class="vzyxlnb8e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:mcp-manifest-outline-bold" /></template>
<style>
.cacmi2bmi {
  d: path("M13 3H9L6 6v15h12V8");
}

.eqk2m_q5d {
  d: path("M9 15h4");
}

.pt-3kkb2k {
  d: path("M9 11h6");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.vzyxlnb8e {
  d: path("M14 11a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
