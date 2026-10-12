<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h-ii44bhq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:shorts-sharp" /></template>
<style>
.h-ii44bhq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 4.75h13.25l.2 1.23l1.6 10.04l.2 1.23l-1.22.25l-4.81 1l-1.22.25l-.33-1.2l-1.34-4.85l-.33-1.2l-.33 1.2l-1.34 4.85l-.33 1.2l-1.22-.25l-4.81-1l-1.22-.25l.2-1.23l1.6-10.04l.2-1.23zM4.5 8h15M11 8l-1 3.25M13 8l1 3.25");
}

</style>
