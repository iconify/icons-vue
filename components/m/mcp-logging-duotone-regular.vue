<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pux-8e3tz"/><path class="cacmi2bmi"/><path class="pty_wsbvs"/><path class="pgcrrz33a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:mcp-logging-duotone-regular" /></template>
<style>
.cacmi2bmi {
  d: path("M13 3H9L6 6v15h12V8");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pgcrrz33a {
  d: path("m10 13.5 2 2 2 -2");
}

.pty_wsbvs {
  d: path("M8 9h8");
}

.pux-8e3tz {
  fill: currentColor;
  d: path("M13 3H9L6 6v15h12V8");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
