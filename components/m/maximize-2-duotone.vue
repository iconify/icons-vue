<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="la86yvriw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:maximize-2-duotone" /></template>
<style>
.la86yvriw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 9L3 3.5C3 3.2239 3.2239 3 3.5 3L9 3M9 9L3.6 3.6M21 9L21 3.5C21 3.2239 20.7761 3 20.5 3L15 3M15 9L20.4 3.6M21 15L21 20.5C21 20.7761 20.7761 21 20.5 21L15 21M15 15L20.4 20.4M3 15L3 20.5C3 20.7761 3.2239 21 3.5 21L9 21M9 15L3.6 20.4");
}

</style>
