<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="ayz0jzbuz"/><path class="ahhqo1b4s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:oven-off-sharp-duotone" /></template>
<style>
.ahhqo1b4s {
  d: path("M1.7071 1.7071L22.2929 22.2929");
}

.ayz0jzbuz {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  fill-rule: evenodd;
  d: path("M21 21L21 22C21 22.5523 20.5523 23 20 23L4 23C3.4477 23 3 22.5523 3 22L3 3L9 9L5 9L5 11L11 11L13 13L8 13L8 15L15 15L21 21ZM4.6569 1L20 1C20.5523 1 21 1.4477 21 2L21 17.3431L14.6569 11L19 11L19 9L12.6569 9L4.6569 1ZM13 6C13 5.4477 12.5523 5 12 5C11.4477 5 11 5.4477 11 6C11 6.5523 11.4477 7 12 7C12.5523 7 13 6.5523 13 6ZM17 6C17 5.4477 16.5523 5 16 5C15.4477 5 15 5.4477 15 6C15 6.5523 15.4477 7 16 7C16.5523 7 17 6.5523 17 6Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
