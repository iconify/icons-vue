<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="amy-wzorq"/><path class="lkje5bbsk"/><path class="eud-3ptuk"/><path class="owdk3hf1a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:share-favorite-duotone-regular" /></template>
<style>
.amy-wzorq {
  fill: currentColor;
  d: path("M2 9a2.5 2.5 0 0 1 5 0 2.5 2.5 0 0 1 5 0l-5 5Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.eud-3ptuk {
  d: path("M15 12h7");
}

.lkje5bbsk {
  d: path("M2 9a2.5 2.5 0 0 1 5 0 2.5 2.5 0 0 1 5 0l-5 5Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.owdk3hf1a {
  d: path("m18 8 4 4 -4 4");
}

</style>
