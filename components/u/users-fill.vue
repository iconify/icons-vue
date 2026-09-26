<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ief54hbis"/><path class="aaf9dhb8c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:users-fill" /></template>
<style>
.aaf9dhb8c {
  fill: currentColor;
  d: path("M13 7C13 9.20914 11.2091 11 9 11C6.79086 11 5 9.20914 5 7C5 4.79086 6.79086 3 9 3C11.2091 3 13 4.79086 13 7ZM8 13H10C13.866 13 17 16.134 17 20C17 21.1046 16.1046 22 15 22H3C1.89543 22 1 21.1046 1 20C1 16.134 4.13401 13 8 13Z");
  stroke: none;
}

.ief54hbis {
  d: path("M16 4C17.6569 4 19 5.34315 19 7C19 8.65685 17.6569 10 16 10M18.3333 14.4713C20.554 15.409 22 17.589 22 20C22 20.5523 21.5523 21 21 21");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
