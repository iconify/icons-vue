<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="fgyarr_hl"/><path class="j64wejbxo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:sliders-2-vertical-duotone" /></template>
<style>
.fgyarr_hl {
  stroke-opacity: 0.4;
  d: path("M7 3L7 6M7 14L7 21M17 3L17 10M17 18L17 21");
}

.j64wejbxo {
  fill: currentColor;
  d: path("M3 9C3 6.7909 4.7909 5 7 5C9.2091 5 11 6.7909 11 9L11 11C11 13.2091 9.2091 15 7 15C4.7909 15 3 13.2091 3 11L3 9ZM13 13C13 10.7909 14.7909 9 17 9C19.2091 9 21 10.7909 21 13L21 15C21 17.2091 19.2091 19 17 19C14.7909 19 13 17.2091 13 15L13 13Z");
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
