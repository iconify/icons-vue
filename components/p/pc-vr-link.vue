<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="za003gooh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pc-vr-link" /></template>
<style>
.za003gooh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.125 3h2.75A2.625 2.625 0 0 1 10.5 5.625v1.75A2.625 2.625 0 0 1 7.875 10h-2.75A2.625 2.625 0 0 1 2.5 7.375v-1.75A2.625 2.625 0 0 1 5.125 3M6.5 10v3m-2 0h4m7-9h4a2 2 0 0 1 2 2v2.5a2 2 0 0 1-2 2h-.25L17.5 8.75l-1.75 1.75h-.25a2 2 0 0 1-2-2V6a2 2 0 0 1 2-2m-10 14.5h13M8 16l-2.5 2.5L8 21m8-5l2.5 2.5L16 21");
}

</style>
