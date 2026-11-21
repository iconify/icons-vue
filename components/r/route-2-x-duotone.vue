<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="gcdj83b-c"/><path class="scs7_dbhx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:route-2-x-duotone" /></template>
<style>
.gcdj83b-c {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M8.8285 16.1715C9.5513 16.8943 10 17.8957 10 19C10 21.2093 8.2093 23 6 23C3.7907 23 2 21.2093 2 19C2 16.7907 3.7907 15 6 15C7.1043 15 8.1057 15.4487 8.8285 16.1715Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.scs7_dbhx {
  d: path("M11 5H10.5C8.567 5 7 6.567 7 8.5C7 10.433 8.567 12 10.5 12H14.5C16.433 12 18 13.567 18 15.5C18 17.433 16.433 19 14.5 19H9M15 2L21 8M21 2L15 8");
}

</style>
