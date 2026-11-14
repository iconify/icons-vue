<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qc-6x4oxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:polymer-chain" /></template>
<style>
.qc-6x4oxo {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M15.25 5.5q0-3.25 3.25-3.25q1.346 0 2.298.952T21.75 5.5t-.952 2.298t-2.298.952q0 3.25-3.25 3.25q0 3.25-3.25 3.25q0 3.25-3.25 3.25q0 3.25-3.25 3.25T2.25 18.5t3.25-3.25Q5.5 12 8.75 12q0-3.25 3.25-3.25q0-3.25 3.25-3.25");
}

</style>
