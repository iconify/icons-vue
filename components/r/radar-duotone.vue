<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="h4kzzjb5r"/><path class="qwr8fublv"/><path class="d-a_qsb5c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:radar-duotone" /></template>
<style>
.d-a_qsb5c {
  fill: currentColor;
  d: path("M13.5 12C13.5 12.8284 12.8284 13.5 12 13.5C11.1716 13.5 10.5 12.8284 10.5 12C10.5 11.1716 11.1716 10.5 12 10.5C12.8284 10.5 13.5 11.1716 13.5 12Z");
  stroke: none;
}

.h4kzzjb5r {
  stroke-opacity: 0.4;
  d: path("M16.2426 7.7574C15.1174 6.6321 13.5913 6 12 6C8.6863 6 6 8.6863 6 12C6 15.3137 8.6863 18 12 18C15.3137 18 18 15.3137 18 12C18 11.8887 17.9969 11.7773 17.9907 11.6661");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qwr8fublv {
  d: path("M21.3092 8.3477C21.7657 9.5113 22 10.7501 22 12C22 17.5228 17.5228 22 12 22C6.4772 22 2 17.5228 2 12C2 6.4772 6.4772 2 12 2C14.6522 2 17.1957 3.0536 19.0711 4.9289L12 12");
}

</style>
