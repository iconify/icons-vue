<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="g_eatebwd"/><path class="prj9u5frn"/><path class="neof5acyb"/><path class="jg5yyubai"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:swimming-race-outline-regular" /></template>
<style>
.g_eatebwd {
  d: path("M5 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.jg5yyubai {
  d: path("M3 16c3 -2 6 2 9 0s6 2 9 0");
}

.neof5acyb {
  d: path("m14 10 4 -4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.prj9u5frn {
  d: path("M9 10h5");
}

</style>
