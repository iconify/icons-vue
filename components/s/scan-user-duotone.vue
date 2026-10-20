<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="s-_3y1_8e"/><path clip-rule="evenodd" class="b74w_2htl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:scan-user-duotone" /></template>
<style>
.b74w_2htl {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14.5 7.5C14.5 8.8807 13.3807 10 12 10C10.6193 10 9.5 8.8807 9.5 7.5C9.5 6.1193 10.6193 5 12 5C13.3807 5 14.5 6.1193 14.5 7.5ZM11 12L13 12C15.2092 12 17 13.7908 17 16C17 17.1046 16.1046 18 15 18L9 18C7.8954 18 7 17.1046 7 16C7 13.7908 8.7908 12 11 12Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.s-_3y1_8e {
  stroke-opacity: 0.4;
  d: path("M3 8L3 6C3 4.3431 4.3431 3 6 3L8 3M16 3L18 3C19.6569 3 21 4.3431 21 6L21 8M21 16L21 18C21 19.6569 19.6569 21 18 21L16 21M8 21L6 21C4.3431 21 3 19.6569 3 18L3 16");
}

</style>
