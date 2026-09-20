<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="se8tg3byo"/><path class="ayfng4o1h"/><path class="pg4kk0y8v"/><path class="sy7mvubrh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:pulley-outline-regular" /></template>
<style>
.ayfng4o1h {
  d: path("M5 6v10");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pg4kk0y8v {
  d: path("M13 6v7");
}

.se8tg3byo {
  d: path("M5 6a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

.sy7mvubrh {
  d: path("M9 13h8v6H9Z");
}

</style>
