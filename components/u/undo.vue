<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v1cfk4b4e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:undo" /></template>
<style>
.v1cfk4b4e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M21 17.9998C21 13.9534 18.6274 10.283 14.9378 8.6216C11.2482 6.9602 6.9273 7.6166 3.8975 10.2987M3 6.0002V11H8");
}

</style>
