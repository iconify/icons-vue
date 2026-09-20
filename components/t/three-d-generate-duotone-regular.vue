<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="qj6ch5btr"/><path class="ryy49t53l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:three-d-generate-duotone-regular" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qj6ch5btr {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m12 2 6 6v8l-6 6 -6 -6V8ZM6 8l6 6 6 -6m-6 6v8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ryy49t53l {
  d: path("m12 2 6 6v8l-6 6 -6 -6V8ZM6 8l6 6 6 -6m-6 6v8");
}

</style>
