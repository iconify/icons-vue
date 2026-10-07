<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pp_et7bgg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:stethoscope-sharp" /></template>
<style>
.pp_et7bgg {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 15C2.9955 15 1.7856 8.2335 2.0294 4.623L2.139 3L6.117 3M8 15C13.0045 15 14.2144 8.2335 13.9706 4.623L13.861 3L9.883 3M20 12L20 15C20 18.3137 17.3137 21 14 21C10.6863 21 8 18.3137 8 15M22 10C22 11.1046 21.1046 12 20 12C18.8954 12 18 11.1046 18 10C18 8.8954 18.8954 8 20 8C21.1046 8 22 8.8954 22 10Z");
}

</style>
