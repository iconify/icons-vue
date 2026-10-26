<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="z4re-xbrw"/><path class="ztzk7sbka"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:tram-front-off-sharp-fill" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.z4re-xbrw {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.432 5L20 5C20.5523 5 21 5.4477 21 6L21 17.3431L14.6569 11L19 11L19 7L10.6569 7L8.6569 5L11.568 5C11.568 4.9922 11.5698 4.9846 11.5733 4.9776L11.9553 4.2137C11.9637 4.1968 11.9811 4.1861 12 4.1861C12.0189 4.1861 12.0363 4.1968 12.0447 4.2137L12.4267 4.9776C12.4302 4.9846 12.432 4.9922 12.432 5ZM6.9999 6.9999L5.4909 7C5.2201 7.0049 5.0024 7.2245 5 7.4954L5 11L8.1716 10.9999L10.9999 10.9999L20.7071 20.7071C20.5198 20.8949 20.2653 21.0003 20 21L4 21C3.4477 21 3 20.5523 3 20L3 6C2.9999 5.4477 3.4477 4.9999 4 4.9999L4.9999 4.9999L6.9999 6.9999ZM9 16C9 15.4477 8.5523 15 8 15C7.4477 15 7 15.4477 7 16C7 16.5523 7.4477 17 8 17C8.5523 17 9 16.5523 9 16Z");
  stroke: none;
}

.ztzk7sbka {
  d: path("M8 20L6.7236 22.5528M16 20L17.2764 22.5528M7 2L17 2M10.5314 4.9372L12 2L14 6M1.7071 1.7071L22.2929 22.2929");
}

</style>
