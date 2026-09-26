<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="teyv8_8vu"/><path class="ku8rdplcq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:mouse-two-tone" /></template>
<style>
.ku8rdplcq {
  d: path("M12 3C15.3137 3 18 5.6863 18 9L18 15C18 18.3137 15.3137 21 12 21C8.6863 21 6 18.3137 6 15L6 9C6 5.6863 8.6863 3 12 3ZM12 7L12 8");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.teyv8_8vu {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 2C15.866 2 19 5.134 19 9L19 15C19 18.866 15.866 22 12 22C8.134 22 5 18.866 5 15L5 9C5 5.134 8.134 2 12 2Z");
  stroke: none;
}

</style>
