<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sn8ra-bhi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:transfer-between-accounts" /></template>
<style>
.sn8ra-bhi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 4h8v7h-8Zm11 9h8v7h-8ZM13 7.5h5m-2-2l2 2l-2 2m-5 7H6m2-2l-2 2l2 2");
}

</style>
