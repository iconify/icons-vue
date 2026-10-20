<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hew4v6brt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:sigma-two-tone" /></template>
<style>
.hew4v6brt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M18 3L7.0019 3C6.1681 3 5.7005 3.9604 6.2147 4.6168L11.5167 11.3832C11.8005 11.7454 11.8005 12.2546 11.5167 12.6168L6.2147 19.3832C5.7005 20.0396 6.1681 21 7.0019 21L18 21");
}

</style>
