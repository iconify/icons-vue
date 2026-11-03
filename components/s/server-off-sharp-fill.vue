<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="it3rj-b5b"/><path class="ahhqo1b4s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:server-off-sharp-fill" /></template>
<style>
.ahhqo1b4s {
  d: path("M1.7071 1.7071L22.2929 22.2929");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.it3rj-b5b {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11 11L4 11C3.4477 11 3 10.5523 3 10L3 3L11 11ZM21 21L21 22C21 22.5523 20.5523 23 20 23L4 23C3.4477 23 3 22.5523 3 22L3 14C3 13.4477 3.4477 13 4 13L13 13L21 21ZM9 18C9 17.4477 8.5523 17 8 17C7.4477 17 7 17.4477 7 18C7 18.5523 7.4477 19 8 19C8.5523 19 9 18.5523 9 18ZM13 18C13 17.4477 12.5523 17 12 17C11.4477 17 11 17.4477 11 18C11 18.5523 11.4477 19 12 19C12.5523 19 13 18.5523 13 18ZM4.6569 1L20 1C20.5523 1 21 1.4477 21 2L21 10C21 10.5523 20.5523 11 20 11L14.6569 11L4.6569 1ZM16.6569 13L20 13C20.5523 13 21 13.4477 21 14L21 17.3431L16.6569 13ZM13 6C13 5.4477 12.5523 5 12 5C11.4477 5 11 5.4477 11 6C11 6.5523 11.4477 7 12 7C12.5523 7 13 6.5523 13 6Z");
  stroke: none;
}

</style>
