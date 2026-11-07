<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="cz5gjqbes"/><path class="zsbo7sb4n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:packages-duotone-sharp" /></template>
<style>
.cz5gjqbes {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M16.947 4.356a1 1 0 0 1 .553.894v5.007l3.947 1.974a1 1 0 0 1 .553.894v5.625a1 1 0 0 1-.553.894l-4.5 2.25a1 1 0 0 1-.894 0L12 19.868l-4.053 2.026a1 1 0 0 1-.894 0l-4.5-2.25A1 1 0 0 1 2 18.75v-5.625c0-.379.214-.725.553-.894L6.5 10.257V5.25c0-.379.214-.725.553-.894l4.5-2.25a1 1 0 0 1 .894 0Z");
}

.ft5dv1b6b {
  fill: none;
}

.zsbo7sb4n {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m12 3l4.5 2.25v5.625l4.5 2.25v5.625L16.5 21L12 18.75L7.5 21L3 18.75v-5.625l4.5-2.25V5.25zM7.5 5.25L12 7.5l4.5-2.25M12 7.5v5.625m-4.5-2.25l4.5 2.25l4.5-2.25M3 13.125l4.5 2.25l4.5-2.25l4.5 2.25l4.5-2.25m-13.5 2.25V21m4.5-7.875v5.625m4.5-3.375V21");
}

</style>
