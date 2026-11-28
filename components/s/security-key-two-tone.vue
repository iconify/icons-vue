<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="weutyrbok"/><path class="vz2p4nb5u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:security-key-two-tone" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.vz2p4nb5u {
  d: path("M9 2L15 2C16.6569 2 18 3.3431 18 5L18 13C18 14.6569 16.6569 16 15 16L9 16C7.3431 16 6 14.6569 6 13L6 5C6 3.3431 7.3431 2 9 2ZM9 16V21C9 21.5523 9.4477 22 10 22H14C14.5523 22 15 21.5523 15 21V16M14 9C14 10.1046 13.1046 11 12 11C10.8954 11 10 10.1046 10 9C10 7.8954 10.8954 7 12 7C13.1046 7 14 7.8954 14 9Z");
}

.weutyrbok {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M8 16.874C6.2747 16.43 5 14.8639 5 13L5 5C5 2.7908 6.7908 1 9 1L15 1C17.2092 1 19 2.7908 19 5L19 9L19 13C19 14.8639 17.7253 16.43 16 16.874L16 21C16 22.1046 15.1046 23 14 23L10 23C8.8954 23 8 22.1046 8 21Z");
  stroke: none;
}

</style>
