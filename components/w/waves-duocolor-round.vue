<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="f6e9ytbin"/><path class="o5scq4bwj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:waves-duocolor-round" /></template>
<style>
.f6e9ytbin {
  stroke-opacity: 0.4;
  d: path("M4 13c2 0 2-2 4-2s2 2 4 2s2-2 4-2s2 2 4 2");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o5scq4bwj {
  d: path("M4 7c2 0 2-2 4-2s2 2 4 2s2-2 4-2s2 2 4 2M4 19c2 0 2-2 4-2s2 2 4 2s2-2 4-2s2 2 4 2");
}

</style>
