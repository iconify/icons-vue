<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="bh4biibbp"/><path class="b93v0obyy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:nda-document-sharp" /></template>
<style>
.b93v0obyy {
  d: path("M7.75 5.5h8.5V8h-8.5zm0 5.5h8.5m-8.5 3h5.5v2.5h-5.5z");
}

.bh4biibbp {
  d: path("M4.75 2.75h14.5v18.5H4.75z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
