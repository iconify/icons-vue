<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gw_nvvbaz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:weight" /></template>
<style>
.gw_nvvbaz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8.3336 9L15.6664 9C16.4739 9 17.2022 9.4856 17.5127 10.2311L20.8442 18.2311C21.3928 19.5484 20.4249 21 18.998 21L5.002 21C3.5751 21 2.6072 19.5484 3.1558 18.2311L6.4873 10.2311C6.7978 9.4856 7.5261 9 8.3336 9ZM15 6C15 7.6569 13.6569 9 12 9C10.3431 9 9 7.6569 9 6C9 4.3431 10.3431 3 12 3C13.6569 3 15 4.3431 15 6Z");
}

</style>
