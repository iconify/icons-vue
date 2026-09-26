<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path clip-rule="evenodd" class="nmx9-c4kv"/><path class="xexl16bfr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:search-plus-fill" /></template>
<style>
.nmx9-c4kv {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18 10C18 14.4183 14.4183 18 10 18C5.5817 18 2 14.4183 2 10C2 5.5817 5.5817 2 10 2C14.4183 2 18 5.5817 18 10ZM11 9L13 9C13.5523 9 14 9.4477 14 10C14 10.5523 13.5523 11 13 11L11 11L11 13C11 13.5523 10.5523 14 10 14C9.4477 14 9 13.5523 9 13L9 11L7 11C6.4477 11 6 10.5523 6 10C6 9.4477 6.4477 9 7 9L9 9L9 7C9 6.4477 9.4477 6 10 6C10.5523 6 11 6.4477 11 7L11 9Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.xexl16bfr {
  d: path("M15 15L21 21");
}

</style>
