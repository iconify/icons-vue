<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="cphlk2bgi"/><path class="zy54a7bml"/><path class="t7ql4f28h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:moving-day-outline-regular" /></template>
<style>
.cphlk2bgi {
  d: path("M3 19v-7l6 -6 6 6v7Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.t7ql4f28h {
  d: path("m19 10 2 2 -2 2");
}

.zy54a7bml {
  d: path("M17 12h4");
}

</style>
