<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="cc50cvs0o"/><path class="er1p0-brb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-more-horizontal" /></template>
<style>
.cc50cvs0o {
  d: path("M6 3H18C19.6569 3 21 4.34315 21 6V18C21 19.6569 19.6569 21 18 21H6C4.34315 21 3 19.6569 3 18V6C3 4.34315 4.34315 3 6 3Z");
}

.er1p0-brb {
  fill: currentColor;
  d: path("M7.3333 10.6667C8.0697 10.6667 8.6666 11.2636 8.6666 12C8.6666 12.7364 8.0697 13.3333 7.3333 13.3333C6.5969 13.3333 6 12.7364 6 12C6 11.2636 6.5969 10.6667 7.3333 10.6667ZM12 10.6667C12.7364 10.6667 13.3333 11.2636 13.3333 12C13.3333 12.7364 12.7364 13.3333 12 13.3333C11.2636 13.3333 10.6667 12.7364 10.6667 12C10.6667 11.2636 11.2636 10.6667 12 10.6667ZM16.6667 10.6667C17.4031 10.6667 18 11.2636 18 12C18 12.7364 17.4031 13.3333 16.6667 13.3333C15.9303 13.3333 15.3334 12.7364 15.3334 12C15.3334 11.2636 15.9303 10.6667 16.6667 10.6667Z");
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
