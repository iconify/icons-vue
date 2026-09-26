<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="xbogfeb0h"/><path class="lm6_mj63l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:sunset-two-tone" /></template>
<style>
.lm6_mj63l {
  d: path("M7.5 18C7.5 15.5147 9.5147 13.5 12 13.5C14.4853 13.5 16.5 15.5147 16.5 18M2 18H3.5M20.5 18H22M4.9289 10.9289L5.9896 11.9896M19.0711 10.9289L18.0104 11.9896");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.xbogfeb0h {
  stroke-opacity: 0.4;
  d: path("M2 22H22M12 2V9M8.5 5.5L12 9L15.5 5.5");
}

</style>
