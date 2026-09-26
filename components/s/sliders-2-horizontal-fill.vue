<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="h181z6xlz"/><path class="d8dm5piln"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:sliders-2-horizontal-fill" /></template>
<style>
.d8dm5piln {
  d: path("M3 7H6M14 7H21M3 17H10M18 17H21");
}

.h181z6xlz {
  fill: currentColor;
  d: path("M9 3L11 3C13.2091 3 15 4.7909 15 7C15 9.2091 13.2091 11 11 11L9 11C6.7909 11 5 9.2091 5 7C5 4.7909 6.7909 3 9 3ZM13 13L15 13C17.2091 13 19 14.7909 19 17C19 19.2091 17.2091 21 15 21L13 21C10.7909 21 9 19.2091 9 17C9 14.7909 10.7909 13 13 13Z");
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
