<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path clip-rule="evenodd" class="rz65w3b9a"/><path class="ft620tbar"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:vector-skew-fill" /></template>
<style>
.ft620tbar {
  d: path("M12 5H17M19 7L14 17M12 19H7M5 17L10 7");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rz65w3b9a {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10 2L11 2C12.1046 2 13 2.8954 13 4L13 6C13 7.1046 12.1046 8 11 8L9 8C7.8954 8 7 7.1046 7 6L7 4C7 2.8954 7.8954 2 9 2ZM19 2L20 2C21.1046 2 22 2.8954 22 4L22 6C22 7.1046 21.1046 8 20 8L18 8C16.8954 8 16 7.1046 16 6L16 4C16 2.8954 16.8954 2 18 2ZM14 16L15 16C16.1046 16 17 16.8954 17 18L17 20C17 21.1046 16.1046 22 15 22L13 22C11.8954 22 11 21.1046 11 20L11 18C11 16.8954 11.8954 16 13 16ZM5 16L6 16C7.1046 16 8 16.8954 8 18L8 20C8 21.1046 7.1046 22 6 22L4 22C2.8954 22 2 21.1046 2 20L2 18C2 16.8954 2.8954 16 4 16Z");
  stroke: none;
}

</style>
