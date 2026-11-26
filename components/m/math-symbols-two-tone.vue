<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="q0pjmpbqi"/><path clip-rule="evenodd" class="jrols_urv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:math-symbols-two-tone" /></template>
<style>
.jrols_urv {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19.3333 14C19.3333 14.7364 18.7364 15.3333 18 15.3333C17.2636 15.3333 16.6667 14.7364 16.6667 14C16.6667 13.2636 17.2636 12.6667 18 12.6667C18.7364 12.6667 19.3333 13.2636 19.3333 14ZM19.3333 20.6667C19.3333 21.4031 18.7364 22 18 22C17.2636 22 16.6667 21.4031 16.6667 20.6667C16.6667 19.9303 17.2636 19.3334 18 19.3334C18.7364 19.3334 19.3333 19.9303 19.3333 20.6667Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.q0pjmpbqi {
  d: path("M6 3L6 9M3 6L9 6M15 6L21 6M3 14.3333L9 20.3333M9 14.3333L3 20.3333M15 17.3333L21 17.3333");
}

</style>
