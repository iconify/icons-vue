<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="s446_nmsp"/><path class="edxkohbgy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:timer-fast-duotone" /></template>
<style>
.edxkohbgy {
  d: path("M9 2L15 2M12 2L12 6M12 14L12 10M17.6569 8.3431L19 7M4 12L8 12M4 16L7 16");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.s446_nmsp {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 5C16.9706 5 21 9.0294 21 14C21 18.9706 16.9706 23 12 23C7.0294 23 3 18.9706 3 14C3 9.0294 7.0294 5 12 5Z");
  stroke: none;
}

</style>
