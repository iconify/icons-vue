<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="yokhjnhsx"/><path class="m9ovzibjs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:target-arrow-two-tone" /></template>
<style>
.m9ovzibjs {
  d: path("M21.5168 8.9289C21.8369 9.9212 22 10.9574 22 12C22 17.5228 17.5228 22 12 22C6.4772 22 2 17.5228 2 12C2 6.4772 6.4772 2 12 2C13.0426 2 14.0788 2.1631 15.0711 2.4832M12 12L16.2426 7.75736M16.2426 7.75736L19.0711 4.9289M16.2426 7.75736C15.1568 6.67157 13.6568 6 12 6C8.6863 6 6 8.6863 6 12C6 15.3137 8.6863 18 12 18C15.3137 18 18 15.3137 18 12C18 10.3432 17.3284 8.84315 16.2426 7.75736ZM19.0711 4.9289V2M19.0711 4.9289H22");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.yokhjnhsx {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M7.0503 7.0503C5.7846 8.3159 5 10.0673 5 12C5 15.866 8.134 19 12 19C15.866 19 19 15.866 19 12C19 10.0673 18.2154 8.3159 16.9497 7.0502C15.684 5.7846 13.9327 5 12 5C10.0673 5 8.3159 5.7846 7.0503 7.0503Z");
  stroke: none;
}

</style>
