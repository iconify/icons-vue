<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="r4pi6ubuy"/><path class="mr4puvbrd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:remodel-house-sharp" /></template>
<style>
.mr4puvbrd {
  d: path("m11.34 15.09l3.75-3.75l.42-.42l.43.42l.91.92l.43.42l-.42.42l-3.76 3.76l-.42.42l-.42-.43l-.92-.91l-.42-.43zm3.64-.11l4.95 4.95");
}

.r4pi6ubuy {
  d: path("M2.75 18.75V7.95l.78-.62l4.94-3.96l.78-.62l.78.62l4.94 3.96l.78.62v11.8h-13z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
