<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l23mpj4py"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:test-run" /></template>
<style>
.l23mpj4py {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m6.278 3.883l9.61 5.835a1.5 1.5 0 0 1 0 2.564l-9.61 5.835A1.5 1.5 0 0 1 4 16.834V5.166a1.5 1.5 0 0 1 2.278-1.283M14.75 18l2 2L21 15.75");
}

</style>
