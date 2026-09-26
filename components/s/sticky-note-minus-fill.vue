<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path clip-rule="evenodd" class="i5x5t8b8o"/><path class="h-3eqtbix"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:sticky-note-minus-fill" /></template>
<style>
.h-3eqtbix {
  d: path("M15 18L21 18");
}

.i5x5t8b8o {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6 2L15 2C15.2652 2 15.5196 2.1054 15.7071 2.2929L21.7071 8.2929C21.8946 8.4804 22 8.7348 22 9L22 11C22 11.5523 21.5523 12 21 12L15 12C13.3431 12 12 13.3431 12 15L12 21C12 21.5523 11.5523 22 11 22L6 22C3.7909 22 2 20.2091 2 18L2 6C2 3.7909 3.7909 2 6 2ZM15 6C15 7.6569 16.3431 9 18 9L19.5858 9L15 4.4142Z");
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
