<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="z2zm0yl7b"/><path class="n88s80lvq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:users-duotone" /></template>
<style>
.n88s80lvq {
  d: path("M16 3C17.6569 3 19 4.3431 19 6C19 7.6569 17.6569 9 16 9M18.3333 13.4713C20.554 14.409 22 16.589 22 19V20C22 20.5523 21.5523 21 21 21");
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
