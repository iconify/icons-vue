<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="tcft5unkl"/><path clip-rule="evenodd" class="bptmxumgf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:user-voice-sharp-fill" /></template>
<style>
.bptmxumgf {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9 2C11.071 2 13 3.929 13 6C13 8.071 11.071 10 9 10C6.929 10 5 8.071 5 6C5 3.929 6.929 2 9 2ZM8 12H10C13.728 12 17 15.272 17 19V21C17 21.552 16.552 22 16 22H2C1.448 22 1 21.552 1 21V19C1 15.272 4.272 12 8 12Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.tcft5unkl {
  d: path("M17.25 2.333L17.485 3C17.826 3.964 18 4.978 18 6C18 7.022 17.826 8.037 17.485 9L17.25 9.667M21.467 2.231L21.649 3C21.882 3.983 22 4.99 22 6C22 8.282 21.399 10.524 20.258 12.5L19.97 13");
}

</style>
