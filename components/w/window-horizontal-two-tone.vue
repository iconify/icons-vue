<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="iwuq3xbhi"/><path class="fks3-_p_m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:window-horizontal-two-tone" /></template>
<style>
.fks3-_p_m {
  d: path("M3 19V6C3 5.448 3.448 5 4 5H20C20.552 5 21 5.448 21 6V19M2 19H22M12 5V19M3 12H21");
}

.iwuq3xbhi {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M20 4C21.105 4 22 4.895 22 6V18C22.552 18 23 18.448 23 19C23 19.552 22.552 20 22 20H2C1.448 20 1 19.552 1 19C1 18.448 1.448 18 2 18V6C2 4.895 2.895 4 4 4H20Z");
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
