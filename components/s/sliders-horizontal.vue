<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l9be7jb9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:sliders-horizontal" /></template>
<style>
.l9be7jb9i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 5L12 5M21 5L16 5M16 3L16 7M3 12L10 12M21 12L14 12M10 10L10 14M3 19L10 19M21 19L14 19M14 17L14 21");
}

</style>
