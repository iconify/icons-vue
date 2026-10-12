<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ql_iibf2n"/><path class="nfaea-xiv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:mechanical-pencil" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nfaea-xiv {
  d: path("m14.36 7.16l-2.12-2.12l-3.18 3.19M4.67 19.04l.29.29q.28.28.62.07l1.72-1.06q.34-.21.06-.49l-1.21-1.21q-.28-.28-.49.06L4.6 18.42q-.21.34.07.62m-1.09 1.38l1.23-1.23");
}

.ql_iibf2n {
  d: path("m16.13 7.16l.71.71q.53.53 1.06 0l.88-.88q.53-.53 0-1.06l-.71-.71q-.53-.53-1.06 0l-.88.88q-.53.53 0 1.06M6.4 16.88l.72.72q.88.88 1.76 0l7.96-7.96q.88-.88 0-1.76l-.72-.72q-.88-.88-1.76 0L6.4 15.12q-.88.88 0 1.76");
}

</style>
