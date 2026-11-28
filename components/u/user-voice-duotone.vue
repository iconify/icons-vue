<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="z2zm0yl7b"/><path class="c4xxezb-o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:user-voice-duotone" /></template>
<style>
.c4xxezb-o {
  d: path("M17.4853 3C17.8259 3.9635 18 4.978 18 6C18 7.022 17.8259 8.0365 17.4853 9M21.6491 3C21.8822 3.983 22 4.9898 22 6C22 8.282 21.3993 10.5238 20.2583 12.5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.z2zm0yl7b {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M8 12H10C13.866 12 17 15.134 17 19V20C17 21.1046 16.1046 22 15 22H3C1.89543 22 1 21.1046 1 20V19C1 15.134 4.13401 12 8 12ZM13 6C13 8.20914 11.2091 10 9 10C6.79086 10 5 8.20914 5 6C5 3.79086 6.79086 2 9 2C11.2091 2 13 3.79086 13 6Z");
  stroke: none;
}

</style>
