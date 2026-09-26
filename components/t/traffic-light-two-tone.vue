<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="r6cc3pb_a"/><path class="lj1xk3bxv"/><path class="aefmnnbnd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:traffic-light-two-tone" /></template>
<style>
.aefmnnbnd {
  fill: currentColor;
  d: path("M13.5 7C13.5 7.8284 12.8284 8.5 12 8.5C11.1716 8.5 10.5 7.8284 10.5 7C10.5 6.1716 11.1716 5.5 12 5.5C12.8284 5.5 13.5 6.1716 13.5 7ZM13.5 12C13.5 12.8284 12.8284 13.5 12 13.5C11.1716 13.5 10.5 12.8284 10.5 12C10.5 11.1716 11.1716 10.5 12 10.5C12.8284 10.5 13.5 11.1716 13.5 12Z");
  stroke: none;
}

.lj1xk3bxv {
  d: path("M10 2L14 2C15.6569 2 17 3.3431 17 5L17 14C17 15.6569 15.6569 17 14 17L10 17C8.3431 17 7 15.6569 7 14L7 5C7 3.3431 8.3431 2 10 2ZM7 5L5 5M17 5L19 5M7 10L5 10M17 10L19 10M12 17L12 22");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.r6cc3pb_a {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M10 1L14 1C16.2091 1 18 2.7909 18 5L18 14C18 16.2091 16.2091 18 14 18L10 18C7.7909 18 6 16.2091 6 14L6 5C6 2.7909 7.7909 1 10 1Z");
  stroke: none;
}

</style>
