<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="juwk6m2oa"/><path class="iaxzcsu4v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:terminal-cursor-duotone" /></template>
<style>
.iaxzcsu4v {
  stroke-opacity: 0.4;
  d: path("M20 19H13");
}

.juwk6m2oa {
  fill: currentColor;
  d: path("M13.7685 3.77335C14.9255 3.40141 16.0247 4.49133 15.6562 5.65421L15.6542 5.66104L12.5302 15.289C12.1131 16.5848 10.3216 16.6992 9.74409 15.4638L7.78901 11.2831L3.91791 9.64249L3.91889 9.64151C2.64383 9.1059 2.71202 7.2754 4.02534 6.83682L4.03315 6.83389L4.04194 6.83194L13.7685 3.77335Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
