<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k-6a3v2fs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:smartphone" /></template>
<style>
.k-6a3v2fs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10.5 6H13.5M19 18V6C19 3.79086 17.2091 2 15 2H9C6.79086 2 5 3.79086 5 6V18C5 20.2091 6.79086 22 9 22H15C17.2091 22 19 20.2091 19 18Z");
}

</style>
