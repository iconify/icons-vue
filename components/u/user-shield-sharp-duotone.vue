<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="e6n5cdcwd"/><path class="wyulutmwq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:user-shield-sharp-duotone" /></template>
<style>
.e6n5cdcwd {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 22H2C1.44772 22 1 21.5523 1 21V19C1 15.134 4.13402 12 8 12H12V22ZM9 2C11.2092 2 13 3.79082 13 6C13 8.20918 11.2092 10 9 10C6.79094 10 5 8.20921 5 6C5 3.79079 6.79094 2 9 2Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.wyulutmwq {
  d: path("M22 13.6976L22 18.2779L21.3928 19.0631C20.8667 19.7434 20.0327 20.5058 18.863 20.9355C18.6288 21.0215 18.3712 21.0215 18.137 20.9355C16.9673 20.5058 16.1333 19.7434 15.6073 19.0631L15 18.2778L15 13.6976L15.5173 13.6362C16.6758 13.4988 17.5504 12.9203 18.0731 12.4132C18.2974 12.1956 18.7026 12.1956 18.9269 12.4132C19.4496 12.9203 20.3242 13.4988 21.4827 13.6362Z");
}

</style>
