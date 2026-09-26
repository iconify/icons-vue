<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e1ahaabrf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:repeat-1-sharp-fill" /></template>
<style>
.e1ahaabrf {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10.5547 4.2968L12.5 3L12.5 10M3 18L21 18L21 5L15.5 5M6.2929 14.7071L3 18L6.2929 21.2929M3 12L3 5L8 5");
}

</style>
