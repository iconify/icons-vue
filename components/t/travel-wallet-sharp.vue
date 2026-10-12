<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mtan94bij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:travel-wallet-sharp" /></template>
<style>
.mtan94bij {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m5.47 7.27l.81-3.54l.22-.98l.98.22l4.79 1.06l.98.22l-.24.97l-.52 2.06l-.24.97h-7zm-2.72.98h18.5V21H2.75zm0 5h18.5");
}

</style>
