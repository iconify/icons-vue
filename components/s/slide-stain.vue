<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="do75o1b8i"/><path class="lrj_dgb9g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:slide-stain" /></template>
<style>
.do75o1b8i {
  d: path("M4 6.5h16L21.5 8v8L20 17.5H4L2.5 16V8Zm2.5 0v11");
}

.lrj_dgb9g {
  d: path("M13 9.25c1 1.25 2 2.25 2 3.5a2 2 0 0 1-4 0c0-1.25 1-2.25 2-3.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
