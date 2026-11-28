<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ze60n0jsc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-padding-sharp" /></template>
<style>
.ze60n0jsc {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 3L21 3L21 21L3 21ZM9.5 7L14.5 7M17 9.5L17 14.5M9.5 17L14.5 17M7 9.5L7 14.5");
}

</style>
