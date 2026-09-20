<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ietrdurnc"/><path class="acyg6nb1v"/><path class="ibxg-pb4c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:meetup-outline-regular" /></template>
<style>
.acyg6nb1v {
  d: path("M10 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.ibxg-pb4c {
  d: path("M9 13a3 3 0 0 1 6 0");
}

.ietrdurnc {
  d: path("M12 21s-7 -7 -7 -11a7 7 0 0 1 14 0c0 4 -7 11 -7 11");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
