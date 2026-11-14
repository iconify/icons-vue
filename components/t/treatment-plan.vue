<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="i6x6u6jls"/><path class="i54rof36h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:treatment-plan" /></template>
<style>
.i54rof36h {
  d: path("m5.25 5.5l1-.5v3m-1 2.25c0-.5.5-.75 1-.75s1 .25 1 .75c0 .75-2 1.25-2 2.25h2m-2 1.75c.25-.25.65-.5 1-.5c.55 0 1 .35 1 .75c0 .6-.45.75-1 .75c.6 0 1 .35 1 .75c0 .6-.5 1-1 1c-.4 0-.75-.2-1-.5m4-10h4.25M9.25 11h4.25m-4.25 4.5H12m1.934 3.737l5.303-5.303l2.829 2.829l-5.303 5.303Zm2.652-2.651l2.828 2.828");
}

.i6x6u6jls {
  d: path("M10.8 20H3V2.5h13.5v10.2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
