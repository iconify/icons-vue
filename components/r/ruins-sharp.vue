<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="fcmaovbhm"/><path class="zub1c18wr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ruins-sharp" /></template>
<style>
.fcmaovbhm {
  d: path("M3.15 2.75H13l-.25.31l-.5.63L12 4l.28.28l.69.69l.28.28H2.75v-2.5z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zub1c18wr {
  d: path("M3.5 5.25H8v16H3.5zm7 15.6V11l.28-.28l.69-.69l.28-.28l.25.31l.5.63l.25.31l.37-.16l1.01-.43l.37-.16v11h-4zm6.75-3.6h4v4h-4z");
}

</style>
