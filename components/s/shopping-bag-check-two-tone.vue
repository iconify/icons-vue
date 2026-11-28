<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="uk47ojphh"/><path class="s6k304ifj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:shopping-bag-check-two-tone" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.s6k304ifj {
  d: path("M15 11C15 12.6569 13.6569 14 12 14C10.3431 14 9 12.6569 9 11M14 19L16 21L20 17");
}

.uk47ojphh {
  stroke-opacity: 0.4;
  d: path("M4.0572 7H19.9428M10 21H7C5.34315 21 4 19.6569 4 18V7.33333C4 7.11696 4.07018 6.90643 4.2 6.73333L6.1 4.2C6.66656 3.44458 7.55573 3 8.5 3H15.5C16.4443 3 17.3334 3.44458 17.9 4.2L19.8 6.73333C19.9298 6.90643 20 7.11696 20 7.33333V12");
}

</style>
