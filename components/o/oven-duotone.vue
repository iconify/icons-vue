<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="eha2qtbyb"/><path class="zw4ip6e0d"/><path clip-rule="evenodd" class="bzoga7-av"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:oven-duotone" /></template>
<style>
.bzoga7-av {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9 6C9 6.5523 8.5523 7 8 7C7.4477 7 7 6.5523 7 6C7 5.4477 7.4477 5 8 5C8.5523 5 9 5.4477 9 6ZM13 6C13 6.5523 12.5523 7 12 7C11.4477 7 11 6.5523 11 6C11 5.4477 11.4477 5 12 5C12.5523 5 13 5.4477 13 6ZM17 6C17 6.5523 16.5523 7 16 7C15.4477 7 15 6.5523 15 6C15 5.4477 15.4477 5 16 5C16.5523 5 17 5.4477 17 6Z");
  stroke: none;
}

.eha2qtbyb {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M8 1L16 1C18.7614 1 21 3.2386 21 6L21 20C21 21.6569 19.6569 23 18 23L6 23C4.3431 23 3 21.6569 3 20L3 6C3 3.2386 5.2386 1 8 1Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.zw4ip6e0d {
  d: path("M6 10L18 10M9 14L15 14");
}

</style>
