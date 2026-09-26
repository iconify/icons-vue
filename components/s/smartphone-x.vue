<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xg4d5_3hc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:smartphone-x" /></template>
<style>
.xg4d5_3hc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M19 12V6C19 3.79086 17.2091 2 15 2H9C6.79086 2 5 3.79086 5 6V18C5 20.2091 6.79086 22 9 22M19 16L13 22M13 16L19 22M13.5 6H10.5");
}

</style>
