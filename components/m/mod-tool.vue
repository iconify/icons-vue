<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q-hcvnbpa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:mod-tool" /></template>
<style>
.q-hcvnbpa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m21.01 5.25l-1.67 1.67l-2.26-2.26l1.67-1.67a3.1 3.1 0 0 0-3.53 4.37L12.7 9.89a1 1 0 0 0 1.41 1.41l2.52-2.52a3.1 3.1 0 0 0 4.38-3.53M7.5 14.2h9a2.5 2.5 0 0 1 2.45 2l.55 2.55a1.5 1.5 0 0 1-2.55 1.3L15.5 18.7h-7l-1.45 1.35a1.5 1.5 0 0 1-2.55-1.3l.55-2.55a2.5 2.5 0 0 1 2.45-2");
}

</style>
