<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n2kdxccsg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:parking-sharp" /></template>
<style>
.n2kdxccsg {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.5 13V8H12C13.381 8 14.5 9.12 14.5 10.5C14.5 11.88 13.381 13 12 13H9.5ZM9.5 13V17M12 22C6.477 22 2 17.52 2 12C2 6.48 6.477 2 12 2C17.523 2 22 6.48 22 12C22 17.52 17.523 22 12 22Z");
}

</style>
