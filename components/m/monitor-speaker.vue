<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="j5b5mjbbd"/><path clip-rule="evenodd" class="u94m2r1mo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:monitor-speaker" /></template>
<style>
.j5b5mjbbd {
  d: path("M8 4L5 4C3.3431 4 2 5.3431 2 7L2 13C2 14.6569 3.3431 16 5 16L8 16M8 20L6 20M15 4L19 4C20.6569 4 22 5.3431 22 7L22 17C22 18.6569 20.6569 20 19 20L15 20C13.3431 20 12 18.6569 12 17L12 7C12 5.3431 13.3431 4 15 4Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.u94m2r1mo {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19 15C19 16.1046 18.1046 17 17 17C15.8954 17 15 16.1046 15 15C15 13.8954 15.8954 13 17 13C18.1046 13 19 13.8954 19 15ZM18 8C18 8.5523 17.5523 9 17 9C16.4477 9 16 8.5523 16 8C16 7.4477 16.4477 7 17 7C17.5523 7 18 7.4477 18 8Z");
  stroke: none;
}

</style>
