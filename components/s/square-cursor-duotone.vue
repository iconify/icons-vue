<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="lwaj0vjwi"/><path class="i601mue2m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-cursor-duotone" /></template>
<style>
.i601mue2m {
  d: path("M9.88767 16.6457L7.02471 7.66244C6.89855 7.26656 7.27689 6.89543 7.6725 7.02702L16.6515 10.0135C17.0987 10.1623 17.1212 10.7838 16.6859 10.9643L12.9526 12.5116C12.8352 12.5602 12.7403 12.6508 12.6865 12.7654L10.8359 16.7071C10.6392 17.1262 10.0282 17.0866 9.88767 16.6457Z");
}

.lwaj0vjwi {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 6C2 3.79086 3.79086 2 6 2H18C20.2091 2 22 3.79086 22 6V18C22 20.2091 20.2091 22 18 22H6C3.79086 22 2 20.2091 2 18V6Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
