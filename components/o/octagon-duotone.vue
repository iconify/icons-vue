<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jl9fy9sni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:octagon-duotone" /></template>
<style>
.jl9fy9sni {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 14.5645L3 9.4355C3 8.7725 3.2634 8.1366 3.7322 7.6678L7.6678 3.7322C8.1366 3.2634 8.7725 3 9.4355 3L14.5645 3C15.2275 3 15.8634 3.2634 16.3322 3.7322L20.2678 7.6678C20.7366 8.1366 21 8.7725 21 9.4355L21 14.5645C21 15.2275 20.7366 15.8634 20.2678 16.3322L16.3322 20.2678C15.8634 20.7366 15.2275 21 14.5645 21L9.4355 21C8.7725 21 8.1366 20.7366 7.6678 20.2678L3.7322 16.3322C3.2634 15.8634 3 15.2275 3 14.5645Z");
}

</style>
