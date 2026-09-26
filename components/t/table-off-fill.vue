<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="v3liahbge"/><path class="wg2n7g_fm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:table-off-fill" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.v3liahbge {
  fill: currentColor;
  d: path("M3.17157 3.17157C2.42143 3.92172 2 4.93913 2 6V9H9ZM7.94975 3.70711C7.76221 3.51957 7.65685 3.26522 7.65685 3C7.65685 2.44772 8.10457 2 8.65685 2H18C20.20914 2 22 3.79086 22 6V10H14.65685C14.39164 10 14.13728 9.89464 13.94975 9.70711Z");
  stroke: none;
}

.wg2n7g_fm {
  d: path("M20.12132 20.12132C19.55871 20.68393 18.79565 21 18 21H6C4.34315 21 3 19.65685 3 18V6C3 5.20435 3.31607 4.44129 3.87868 3.87868M3 9H9M3 15H15M12 12V21M8.65685 3H18C19.65685 3 21 4.34315 21 6V15.34315M14.65685 9H21M2 2L22 22");
}

</style>
