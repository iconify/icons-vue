<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="agrj6gbpz"/><path class="ryy49t53l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:three-d-generate-duotone-bold" /></template>
<style>
.agrj6gbpz {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m12 2 6 6v8l-6 6 -6 -6V8ZM6 8l6 6 6 -6m-6 6v8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ryy49t53l {
  d: path("m12 2 6 6v8l-6 6 -6 -6V8ZM6 8l6 6 6 -6m-6 6v8");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
