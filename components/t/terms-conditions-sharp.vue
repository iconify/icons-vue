<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="bh4biibbp"/><path class="hup1ljbhq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:terms-conditions-sharp" /></template>
<style>
.bh4biibbp {
  d: path("M4.75 2.75h14.5v18.5H4.75z");
}

.hup1ljbhq {
  d: path("m7.75 7.25l1 1l1.75-2m-2.75 6l1 1l1.75-2m-2.75 6l1 1l1.75-2m2.25-9h3.5m-3.5 5h3.5m-3.5 5h3.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
