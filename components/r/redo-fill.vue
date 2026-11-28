<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v9iq4gtqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:redo-fill" /></template>
<style>
.v9iq4gtqi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 17.9998C3 13.9534 5.3726 10.283 9.0622 8.6216C12.7518 6.9602 17.0727 7.6166 20.1025 10.2987M21 6.0002V11H16");
}

</style>
