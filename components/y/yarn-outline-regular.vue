<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="nrlkc9bnf"/><path class="wkb1-ccil"/><path class="hna3ob3gq"/><path class="ocxbfzbxf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:yarn-outline-regular" /></template>
<style>
.hna3ob3gq {
  d: path("M9 4.5C13 7 17 11 19 15");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.nrlkc9bnf {
  d: path("M4 12a8 8 0 1 0 16 0 8 8 0 1 0 -16 0");
}

.ocxbfzbxf {
  d: path("M12 20c2 1 4 0 5 1");
}

.wkb1-ccil {
  d: path("M5 9c4 2 8 6 10 10");
}

</style>
