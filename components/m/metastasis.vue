<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="cu0o2f7hi"/><path class="wns62rbrd"/><path class="j-a29dbqx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:metastasis" /></template>
<style>
.cu0o2f7hi {
  d: path("m8.25 6.5l1.5 2.25l2.5.5v2.5L13.5 14l-3 .75L9.25 17L7 15.5l-3-.25l.75-3L4 10l2-1.25Z");
}

.j-a29dbqx {
  d: path("m19 2.25l.75 1l1 .25v1l.75 1.25L20 6l-.5 1.25l-1.25-.75L17 6.25L17.25 5L17 3.75l1-.5Zm0 14.5l.75 1l1 .25v1l.75 1.25l-1.5.25l-.5 1.25l-1.25-.75l-1.25-.25l.25-1.25l-.25-1.25l1-.5ZM13.75 8l2-1.75m-2-.5l2 .5l-.25 2M15 16l1.5 1.75m-2 .25l2-.25l.25-2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wns62rbrd {
  fill: currentColor;
  d: path("M7 10.75c1-.75 2.5-.5 3 .75c.25 1.25-.75 2.25-2 2.25c-1-.25-1.75-2.25-1-3Z");
}

</style>
