<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oah0-7b3f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:tumbler-sharp" /></template>
<style>
.oah0-7b3f {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3.6367 7.567C4.9787 7.1908 6.3662 7 7.7604 7C9.1948 7 10.622 7.202 12 7.6C13.378 7.998 14.8052 8.2 16.2396 8.2C17.631 8.2 19.0156 8.0099 20.355 7.6353M3.0014 3L20.9986 3L18.5 21L5.5 21ZM9.8145 13.1807L13.4193 12.4145L14.1855 16.0193L10.5807 16.7855Z");
}

</style>
