<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="b-8hbzwtf"/><path class="d_ua5qf2i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:webinar-sharp" /></template>
<style>
.b-8hbzwtf {
  d: path("M3.75 2.75h16.5v14.5H3.75zm-1 17.75h18.5");
}

.d_ua5qf2i {
  d: path("M9 6.5a2 2 0 1 1 0 4a2 2 0 0 1 0-4ZM5.5 17.25a3.5 3.5 0 0 1 7 0m1.03-10.86a5 5 0 0 1 0 4.22m2.99-4.85a8 8 0 0 1 0 5.48");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
