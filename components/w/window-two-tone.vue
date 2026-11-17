<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="hg-yu_e_h"/><path class="dzsp2i_-j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:window-two-tone" /></template>
<style>
.dzsp2i_-j {
  d: path("M4 21V4C4 3.448 4.4477 3 5 3H19C19.5523 3 20 3.448 20 4V21M2 21H22M12 3V21M4 12H20");
}

.hg-yu_e_h {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M19 2C20.1046 2 21 2.895 21 4V20H22C22.5523 20 23 20.448 23 21C23 21.552 22.5523 22 22 22H2C1.4477 22 1 21.552 1 21C1 20.448 1.4477 20 2 20H3V4C3 2.895 3.8954 2 5 2H19Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
