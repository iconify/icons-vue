<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="tetnah5za"/><path class="av68ewb9k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:unlink-duotone" /></template>
<style>
.av68ewb9k {
  d: path("M6.0353 12C5.2444 12.791 4.8 13.8637 4.8 14.9823C4.8 16.1009 5.2444 17.1737 6.0353 17.9647C6.8263 18.7556 7.8991 19.2 9.0177 19.2C10.1363 19.2 11.209 18.7556 12 17.9647M17.9647 12C18.7556 11.209 19.2 10.1363 19.2 9.0177C19.2 7.8991 18.7556 6.8263 17.9647 6.0353C17.1737 5.2444 16.1009 4.8 14.9823 4.8C13.8637 4.8 12.791 5.2444 12 6.0353");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.tetnah5za {
  stroke-opacity: 0.4;
  d: path("M8.8 6.4L8.8 4M6.4 8.8L4 8.8M15.2 17.6L15.2 20M17.6 15.2L20 15.2");
}

</style>
