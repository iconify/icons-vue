<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="uapk-rbxm"/><path class="n5w2i237e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:sandcastle" /></template>
<style>
.n5w2i237e {
  d: path("M10 21v-5a2 2 0 0 1 4 0v5");
}

.uapk-rbxm {
  d: path("M4 21V11h4V8h2v3h4V8h2v3h4v10Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
