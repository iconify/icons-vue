<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="wfdvwx9xo"/><path class="u09_ukbhb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:user-ban-two-tone" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.u09_ukbhb {
  d: path("M9 3C10.6569 3 12 4.3431 12 6C12 7.6569 10.6569 9 9 9C7.3432 9 6 7.6569 6 6C6 4.3431 7.3432 3 9 3ZM10 21L3 21C2.4477 21 2 20.5523 2 20V19C2 15.6863 4.6863 13 8 13L10 13M15.1716 14.1716L20.8284 19.8284M18 13C20.2092 13 22 14.7908 22 17C22 19.2092 20.2092 21 18 21C15.7908 21 14 19.2092 14 17C14 14.7908 15.7908 13 18 13Z");
}

.wfdvwx9xo {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M10 12C10.5523 12 11 12.4477 11 13L11 21C11 21.5523 10.5523 22 10 22L3 22C1.8954 22 1 21.1046 1 20L1 19C1 15.134 4.134 12 8 12ZM9 2C11.2092 2 13 3.7908 13 6C13 8.2092 11.2092 10 9 10C6.7909 10 5 8.2092 5 6C5 3.7908 6.7909 2 9 2Z");
  stroke: none;
}

</style>
