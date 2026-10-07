<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path clip-rule="evenodd" class="frbqgxfnb"/><path class="ls-3h14ea"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:notebook-fill" /></template>
<style>
.frbqgxfnb {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4 5C4 2.7909 5.7909 1 8 1L18 1C20.2091 1 22 2.7909 22 5L22 19C22 21.2091 20.2091 23 18 23L8 23C5.7909 23 4 21.2091 4 19L4 5ZM18 6C18 5.4477 17.5523 5 17 5C16.4477 5 16 5.4477 16 6L16 18C16 18.5523 16.4477 19 17 19C17.5523 19 18 18.5523 18 18L18 6Z");
  stroke: none;
}

.ls-3h14ea {
  d: path("M3 7L7 7M3 12L7 12M3 17L7 17");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
