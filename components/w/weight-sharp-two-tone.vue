<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="kslpt-npl"/><path class="uvxg8ekcl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:weight-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.kslpt-npl {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M15.4649 8L17 8C17.4304 8 17.8126 8.2754 17.9487 8.6838L21.9487 20.6838C21.9827 20.7857 22 20.8925 22 21C22 21.5523 21.5523 22 21 22L3 22C2.4477 22 2 21.5523 2 21C2 20.8925 2.0173 20.7857 2.0513 20.6838L6.0513 8.6838C6.1874 8.2754 6.5696 8 7 8L8.5351 8C8.1843 7.392 7.9996 6.7024 7.9996 6.0004C7.9996 3.7911 9.7906 2 12 2C14.2094 2 16.0004 3.7911 16.0004 6.0004C16.0004 6.7024 15.8157 7.392 15.4649 8Z");
  stroke: none;
}

.uvxg8ekcl {
  d: path("M7 9L17 9L21 21L3 21ZM15 6C15 7.6569 13.6569 9 12 9C10.3431 9 9 7.6569 9 6C9 4.3431 10.3431 3 12 3C13.6569 3 15 4.3431 15 6Z");
}

</style>
