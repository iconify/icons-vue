<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rnjz_aczh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:sunset-sharp-fill" /></template>
<style>
.rnjz_aczh {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.5 19L7.5 18C7.5 15.5147 9.5147 13.5 12 13.5C14.4853 13.5 16.5 15.5147 16.5 18L16.5 19M1 18L4.5 18M19.5 18L23 18M4.2218 10.2218L6.6967 12.6967M19.7782 10.2218L17.3033 12.6967M1 22L23 22M12 1L12 9M8.2071 5.2071L12 9L15.7929 5.2071");
}

</style>
