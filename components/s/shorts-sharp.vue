<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hhbxsmujj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:shorts-sharp" /></template>
<style>
.hhbxsmujj {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3.998 8V4H19.998V8M3.998 8L2 18.88L9.703 20L12.04 12.23L14.212 20L21.997 18.93L19.998 8M3.998 8H8.998M19.998 8H14.998");
}

</style>
