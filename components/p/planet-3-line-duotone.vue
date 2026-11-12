<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="n75jjimak"/><path class="sxlf-3tyn"/><path class="gshkn9qqt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:planet-3-line-duotone" /></template>
<style>
.gshkn9qqt {
  d: path("M22 12C22 17.5228 17.5228 22 12 22C6.47715 22 2 17.5228 2 12C2 6.47715 6.47715 2 12 2C17.5228 2 22 6.47715 22 12Z");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n75jjimak {
  d: path("M21.1713 8.00739H21C21 8.00739 19.0829 7.86998 16.5 8.75544C15.1257 9.22659 13.5 10.9997 10.4372 10.9997C5.93717 10.9997 3 8.00739 3 8.00739L2.87744 7.89746");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.sxlf-3tyn {
  d: path("M21.6055 14.7907L21.2701 15C19.8903 15.871 17.521 17 14.5092 17C11.172 17 9.40063 15.2269 7.90315 14.7558C5.0888 13.8703 2.99992 14.0077 2.99992 14.0077L2.20691 14.0336");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
