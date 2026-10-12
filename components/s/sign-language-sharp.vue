<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u8tj4kbdp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sign-language-sharp" /></template>
<style>
.u8tj4kbdp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.25 21.25V14L4.6 11.35l-1.022-1.097l2.12-2.12L6.72 9.23l1.03 1.02V4h3v1.5v-2.75h3V5.5V4h3v4v-1.5h3v8a6.75 6.75 0 0 1-3.5 5.9v.85Zm3.5-15.75V10m3-4.5V10m3-2v2m-14-2.75V4.688L5 3m13.75-.25l1.982.518l.518 1.982");
}

</style>
