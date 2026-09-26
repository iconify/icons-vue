<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="haut_8-pk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:table-columns-remove-before" /></template>
<style>
.haut_8-pk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4.1716 19C4.5954 20.1986 5.7287 21 7 21L19 21C20.6569 21 22 19.6569 22 18L22 6C22 4.3431 20.6569 3 19 3L7 3C5.7287 3 4.5954 3.8014 4.1716 5M13 21L13 3M2 9L8 15M8 9L2 15");
}

</style>
