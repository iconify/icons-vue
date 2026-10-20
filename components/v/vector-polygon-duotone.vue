<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="x8yexxb5d"/><path clip-rule="evenodd" class="sks5n_ref"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:vector-polygon-duotone" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.sks5n_ref {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11 1L13 1C14.1046 1 15 1.8954 15 3L15 5C15 6.1046 14.1046 7 13 7L11 7C9.8954 7 9 6.1046 9 5L9 3C9 1.8954 9.8954 1 11 1ZM19 7L21 7C22.1046 7 23 7.8954 23 9L23 11C23 12.1046 22.1046 13 21 13L19 13C17.8954 13 17 12.1046 17 11L17 9C17 7.8954 17.8954 7 19 7ZM16 17L18 17C19.1046 17 20 17.8954 20 19L20 21C20 22.1046 19.1046 23 18 23L16 23C14.8954 23 14 22.1046 14 21L14 19C14 17.8954 14.8954 17 16 17ZM6 17L8 17C9.1046 17 10 17.8954 10 19L10 21C10 22.1046 9.1046 23 8 23L6 23C4.8954 23 4 22.1046 4 21L4 19C4 17.8954 4.8954 17 6 17ZM3 7L5 7C6.1046 7 7 7.8954 7 9L7 11C7 12.1046 6.1046 13 5 13L3 13C1.8954 13 1 12.1046 1 11L1 9C1 7.8954 1.8954 7 3 7Z");
  stroke: none;
}

.x8yexxb5d {
  stroke-opacity: 0.4;
  d: path("M14 5.5L18 8.5M19.4 12L17.6 18M15 20L9 20M6.4 18L4.6 12M6 8.5L10 5.5");
}

</style>
