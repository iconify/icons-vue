<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="v49pi3bmt"/><path class="qoebk6oie"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:sun-medium-fill" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qoebk6oie {
  d: path("M20.5 12L21 12M18.0104 18.0104L18.364 18.364M12 20.5L12 21M5.9896 18.0104L5.636 18.364M3.5 12L3 12M5.9896 5.9896L5.636 5.636M12 3.5L12 3M18.0104 5.9896L18.364 5.636");
}

.v49pi3bmt {
  fill: currentColor;
  d: path("M17.5 12C17.5 15.0376 15.0376 17.5 12 17.5C8.9624 17.5 6.5 15.0376 6.5 12C6.5 8.9624 8.9624 6.5 12 6.5C15.0376 6.5 17.5 8.9624 17.5 12Z");
  stroke: none;
}

</style>
