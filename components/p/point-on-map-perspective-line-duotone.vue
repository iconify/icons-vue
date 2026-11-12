<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="rc4qvxc7z"/><path class="lxvimfgoy"/><path class="k04p0xb8w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:point-on-map-perspective-line-duotone" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k04p0xb8w {
  d: path("M21.1213 21.1213C22 20.2426 22 18.8284 22 16C22 13.1716 22 11.7574 21.1213 10.8787M21.1213 10.8787C20.2426 10 18.8284 10 16 10L8 10C5.17157 10 3.75736 10 2.87868 10.8787C2 11.7574 2 13.1716 2 16C2 18.8284 2 20.2426 2.87868 21.1213C3.75736 22 5.17157 22 8 22H16C18.8284 22 20.2426 22 21.1213 21.1213M21.1213 21.1213V21.1213ZM21.1213 10.8787V10.8787ZM2.87868 10.8787V10.8787ZM2.87868 21.1213V21.1213Z");
}

.lxvimfgoy {
  d: path("M17 8C18.6569 8 20 6.65685 20 5C20 3.34315 18.6569 2 17 2C15.3431 2 14 3.34315 14 5C14 6.65685 15.3431 8 17 8ZM17 8V13");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.rc4qvxc7z {
  d: path("M21.1568 21.0875L11.9996 16.0002M11.9996 16.0002L2.84277 10.9131M11.9996 16.0002L3.0415 21.2697M11.9996 16.0002L11.9999 16");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
