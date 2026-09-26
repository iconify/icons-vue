<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tqlzyghhg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:pound-sterling-sharp-duotone" /></template>
<style>
.tqlzyghhg {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 23L9 22L9 6C9 3.7909 10.7909 2 13 2C15.2091 2 17 3.7909 17 6C17 6.7021 16.8152 7.3919 16.4641 8L16.1754 8.5M5 15L6 15L15 15L16 15M3 22L4 22L20 22L21 22");
}

</style>
