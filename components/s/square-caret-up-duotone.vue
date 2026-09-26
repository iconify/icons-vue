<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="lwaj0vjwi"/><path class="vrxvccc3q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-caret-up-duotone" /></template>
<style>
.lwaj0vjwi {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 6C2 3.79086 3.79086 2 6 2H18C20.2091 2 22 3.79086 22 6V18C22 20.2091 20.2091 22 18 22H6C3.79086 22 2 20.2091 2 18V6Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.vrxvccc3q {
  d: path("M11.5301 7.77326L7.06842 15.7107C6.86937 16.0648 7.12844 16.5 7.5383 16.5H16.4617C16.8716 16.5 17.1306 16.0648 16.9316 15.7107L12.4699 7.77326C12.2651 7.40891 11.7349 7.40891 11.5301 7.77326Z");
}

</style>
