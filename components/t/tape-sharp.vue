<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hydbs_uyl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:tape-sharp" /></template>
<style>
.hydbs_uyl {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M2 8C2 4.6863 6.4772 2 12 2C17.5228 2 22 4.6863 22 8C22 11.3137 17.5228 14 12 14C6.4772 14 2 11.3137 2 8ZM7 8C7 6.8954 9.2386 6 12 6C14.7614 6 17 6.8954 17 8C17 9.1046 14.7614 10 12 10C9.2386 10 7 9.1046 7 8ZM2 8L2 16C2 19.3137 6.4772 22 12 22C17.5228 22 22 19.3137 22 16L22 8M17 13.1962L16 14.5295L17 15.8628L18 17.1962L17 18.5295L16 19.8628L17 21.1962");
}

</style>
