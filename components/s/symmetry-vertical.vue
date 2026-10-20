<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s0glblbpz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:symmetry-vertical" /></template>
<style>
.s0glblbpz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 16.3168L5 7.6832C5 7.2712 5.2527 6.9014 5.6365 6.7516L17.6365 2.0693C18.2922 1.8135 19 2.2971 19 3.0009L19 20.9991C19 21.7029 18.2922 22.1865 17.6365 21.9306L5.6365 17.2484C5.2527 17.0986 5 16.7288 5 16.3168ZM2 12L22 12");
}

</style>
