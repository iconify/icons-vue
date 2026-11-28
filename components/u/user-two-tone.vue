<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="j76g-6tlf"/><path class="mwgk6r75p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:user-two-tone" /></template>
<style>
.j76g-6tlf {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M11 12H13C16.866 12 20 15.134 20 19V20C20 21.1046 19.1046 22 18 22H6C4.89543 22 4 21.1046 4 20V19C4 15.134 7.13401 12 11 12ZM16 6C16 8.20914 14.2091 10 12 10C9.79086 10 8 8.20914 8 6C8 3.79086 9.79086 2 12 2C14.2091 2 16 3.79086 16 6Z");
  stroke: none;
}

.mwgk6r75p {
  d: path("M11 13H13C16.3137 13 19 15.6863 19 19V20C19 20.5523 18.5523 21 18 21H6C5.44772 21 5 20.5523 5 20V19C5 15.6863 7.68629 13 11 13ZM12 3C13.6569 3 15 4.34315 15 6C15 7.65685 13.6569 9 12 9C10.3431 9 9 7.65685 9 6C9 4.34315 10.3431 3 12 3Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
