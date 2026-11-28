<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oe434bcut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:printer-off-sharp" /></template>
<style>
.oe434bcut {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 19L2 19L2 10L10 10M14.6569 10L15.6569 10L22 10L22 16.3431L22 17.3431M6.6569 2L7.6569 2L14 2L18 6L18 10M18 18L18 22L6 22L6 15L15 15M1.7071 1.7071L22.2929 22.2929");
}

</style>
