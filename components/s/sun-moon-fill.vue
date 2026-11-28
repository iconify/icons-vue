<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path clip-rule="evenodd" class="p_zqahbdu"/><path class="anxgl_b6p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:sun-moon-fill" /></template>
<style>
.anxgl_b6p {
  d: path("M13 4.5V2M17.596 6.404L19.364 4.636M19.5 11H22");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p_zqahbdu {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.343 9.343C1.897 10.79 1 12.791 1 15C1 19.418 4.582 23 9 23C13.418 23 17 19.418 17 15C17 14.448 16.552 14 16 14C15.784 14 15.573 14.07 15.4 14.2C14.708 14.719 13.865 15 13 15C10.791 15 9 13.209 9 11C9 10.135 9.281 9.292 9.8 8.6C9.93 8.427 10 8.216 10 8C10 7.448 9.552 7 9 7C6.791 7 4.79 7.896 3.343 9.343Z");
  stroke: none;
}

</style>
