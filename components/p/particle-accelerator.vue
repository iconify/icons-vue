<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zbkwrbc8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:particle-accelerator" /></template>
<style>
.zbkwrbc8q {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.75 13q-.001-3.832 2.708-6.543q2.71-2.71 6.542-2.71q.126 0 .251.003H21.5q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-4.415q.765.515 1.457 1.207Q21.251 9.168 21.25 13q.001 3.832-2.708 6.543q-2.71 2.71-6.542 2.71t-6.542-2.71T2.75 13m5.184-4.066Q6.25 10.618 6.25 13t1.684 4.066T12 18.75t4.066-1.684T17.75 13t-1.684-4.066T12 7.25T7.934 8.934");
}

</style>
