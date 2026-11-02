<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ftgvaiacv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:translate-duotone-sharp" /></template>
<style>
.ftgvaiacv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 3v2M3 5h8M9 5q0 7.5-6 9m1-5c1 3 3.5 4.5 7 5m2 7l4-10l4 10m-6-5h4");
}

</style>
