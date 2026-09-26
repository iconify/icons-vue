<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ov4x-iwjx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:smartphone-arrow-in-up-right" /></template>
<style>
.ov4x-iwjx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M19 12V6C19 3.79086 17.2091 2 15 2H9C6.79086 2 5 3.79086 5 6V18C5 20.2091 6.79086 22 9 22M13.5 6H10.5M13 16H18.4994C18.7756 16 19 16.2239 19 16.5V22M14 21L18.5 16.5");
}

</style>
