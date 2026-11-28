<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yw_62bcsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:sun-moon-sharp" /></template>
<style>
.yw_62bcsn {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 8C5.134 8 2 11.134 2 15C2 18.866 5.134 22 9 22C12.866 22 16 18.866 16 15C15.1345 15.6491 14.0819 16 13 16C10.2386 16 8 13.7614 8 11C8 9.9181 8.3509 8.8655 9 8ZM13 5.5L13 1M16.8891 7.1109L20.0711 3.9289M18.5 11L23 11");
}

</style>
