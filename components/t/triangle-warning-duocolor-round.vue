<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="w30nbkbiw"/><path class="pj75233cd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:triangle-warning-duocolor-round" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pj75233cd {
  d: path("m14.986 5.675l5.5 9C21.912 17.007 20.233 20 17.5 20h-11c-2.733 0-4.412-2.993-2.986-5.325l5.5-9c1.364-2.233 4.608-2.233 5.972 0");
}

.w30nbkbiw {
  stroke-opacity: 0.4;
  d: path("M12 9v4m0 3h.01");
}

</style>
