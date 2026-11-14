<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="s5jni0eub"/><path class="jzd3o5ngp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:review-edit" /></template>
<style>
.jzd3o5ngp {
  d: path("m10.5 5l1 2.25l2.25.25L12 9l.5 2.25l-2-1.25l-2 1.25L9 9L7.25 7.5l2.25-.25Zm10 10l1.5 1.5l-5.5 5.5H15v-1.5Z");
}

.s5jni0eub {
  d: path("M5 2.5h11a2 2 0 0 1 2 2v8a2 2 0 0 1-2 2h-6L6.5 18v-3.5H5a2 2 0 0 1-2-2v-8a2 2 0 0 1 2-2Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
