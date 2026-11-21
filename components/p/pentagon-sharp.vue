<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ntllq-e3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:pentagon-sharp" /></template>
<style>
.ntllq-e3u {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3.0022 10.5712L6.2741 21.0003L17.7259 21.0003L20.9978 10.5712L12 2.9997Z");
}

</style>
