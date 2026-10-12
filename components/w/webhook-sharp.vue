<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oq1c6acky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:webhook-sharp" /></template>
<style>
.oq1c6acky {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M15 5C15 6.6569 13.6569 8 12 8C10.3431 8 9 6.6569 9 5C9 3.3431 10.3431 2 12 2C13.6569 2 15 3.3431 15 5ZM22 19C22 20.6569 20.6569 22 19 22C17.3431 22 16 20.6569 16 19C16 17.3431 17.3431 16 19 16C20.6569 16 22 17.3431 22 19ZM8 19C8 20.6569 6.6569 22 5 22C3.3431 22 2 20.6569 2 19C2 17.3431 3.3431 16 5 16C6.6569 16 8 17.3431 8 19ZM13.3416 7.6833L16.1459 13.2918M16 19L11 19M6.3416 16.3167L9.1459 10.7082");
}

</style>
