<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="r2fk4xb9m"/><path class="umnetetzo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:podium-fill" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.r2fk4xb9m {
  fill: currentColor;
  d: path("M4 17.25V13.75H9V10.25H14V6.75H20V17.25H4Z");
  stroke: none;
}

.umnetetzo {
  d: path("M2 17.25H22M4 17.25V13.75H9V10.25H14V6.75H20V17.25H4Z");
}

</style>
