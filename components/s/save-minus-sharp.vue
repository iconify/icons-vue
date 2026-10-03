<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cbb0b5fde"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:save-minus-sharp" /></template>
<style>
.cbb0b5fde {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 3L17 3L21 7L21 21L3 21L3 3ZM7 3L7 7L13 7L13 3M8 14L16 14");
}

</style>
