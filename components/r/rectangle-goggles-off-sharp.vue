<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b0fazabjp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:rectangle-goggles-off-sharp" /></template>
<style>
.b0fazabjp {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10.6569 6L11.6569 6L22 6L22 16.3431L22 17.3431M18 18L16 18L12 13L8 18L2 18L2 6L6 6M1.7071 1.7071L22.2929 22.2929");
}

</style>
