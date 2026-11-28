<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="gd8mm_39d"/><path clip-rule="evenodd" class="jkt8_jn0i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:speakers" /></template>
<style>
.gd8mm_39d {
  d: path("M4 4.172C2.8015 4.595 2 5.729 2 7V17C2 18.271 2.8015 19.405 4 19.828M11 2H19C20.6569 2 22 3.343 22 5V19C22 20.657 20.6569 22 19 22H11C9.3431 22 8 20.657 8 19V5C8 3.343 9.3431 2 11 2ZM18 15C18 16.657 16.6569 18 15 18C13.3431 18 12 16.657 12 15C12 13.343 13.3431 12 15 12C16.6569 12 18 13.343 18 15Z");
}

.jkt8_jn0i {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16.5 7C16.5 7.828 15.8284 8.5 15 8.5C14.1716 8.5 13.5 7.828 13.5 7C13.5 6.172 14.1716 5.5 15 5.5C15.8284 5.5 16.5 6.172 16.5 7Z");
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
