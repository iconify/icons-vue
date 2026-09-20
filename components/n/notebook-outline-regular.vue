<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="k6fi9qmtq"/><path class="z3c71dbbg"/><path class="s-81egb0f"/><path class="wwlpbw4di"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:notebook-outline-regular" /></template>
<style>
.k6fi9qmtq {
  d: path("M2 5a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.s-81egb0f {
  d: path("M9 9h10");
}

.wwlpbw4di {
  d: path("M9 15h10");
}

.z3c71dbbg {
  d: path("M7 3v18");
}

</style>
