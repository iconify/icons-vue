<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ih2r9krfu"/><path class="szyabkg6c"/><path class="mc9d6_y9s"/><path class="nh-kspbph"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:microphone-line-duotone" /></template>
<style>
.ih2r9krfu {
  d: path("M12 16C9.23858 16 7 13.7614 7 11V8C7 5.23858 9.23858 3 12 3C14.7614 3 17 5.23858 17 8V11C17 13.7614 14.7614 16 12 16Z");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mc9d6_y9s {
  d: path("M13 11L17 11");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.nh-kspbph {
  d: path("M20 10V11C20 15.4183 16.4183 19 12 19M4 10V11C4 15.4183 7.58172 19 12 19M12 19V22");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.szyabkg6c {
  d: path("M13 8L17 8");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
