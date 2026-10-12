<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="dom1_xfmh"/><path class="d7rk5-ftp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:mechanical-pencil-sharp" /></template>
<style>
.d7rk5-ftp {
  d: path("m14.36 7.16l-2.12-2.12l-3.18 3.19M4.67 19.04l.29.29l.28.28l.34-.21l1.72-1.06l.34-.21l-.28-.28l-1.21-1.21l-.28-.28l-.21.34l-1.06 1.72l-.21.34zm-1.09 1.38l1.23-1.23");
}

.dom1_xfmh {
  d: path("m16.13 7.16l.71.71l.53.53l.53-.53l.88-.88l.53-.53l-.53-.53l-.71-.71l-.53-.53l-.53.53l-.88.88l-.53.53zM6.4 16.88l.72.72l.88.88l.88-.88l7.96-7.96l.88-.88l-.88-.88l-.72-.72l-.88-.88l-.88.88l-7.96 7.96l-.88.88z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
