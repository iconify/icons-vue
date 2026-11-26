<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ibgrvybad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:message-square-lock" /></template>
<style>
.ibgrvybad {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M21 8L21 6C21 4.3431 19.6569 3 18 3L6 3C4.3431 3 3 4.3431 3 6L3 21L7 17L10 17M15 16L20 16C20.5523 16 21 16.4477 21 17L21 20C21 20.5523 20.5523 21 20 21L15 21C14.4477 21 14 20.5523 14 20L14 17C14 16.4477 14.4477 16 15 16ZM15.5 16L15.5 14C15.5 12.8954 16.3954 12 17.5 12C18.6046 12 19.5 12.8954 19.5 14L19.5 16");
}

</style>
