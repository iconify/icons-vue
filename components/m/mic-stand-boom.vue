<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ol79hfiqd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:mic-stand-boom" /></template>
<style>
.ol79hfiqd {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.507 8.435L4.67 9.827q-.134.065-.233.177q-.098.112-.147.253t-.038.29q.009.149.075.283q.032.067.077.125q.045.059.1.108t.12.086q.064.037.133.061q.07.024.144.033t.146.005q.074-.004.146-.023q.071-.019.137-.052l1.92-.941v4.983l-3.811 4.287q-.099.111-.148.252t-.04.29t.074.283t.177.234t.252.148t.29.04t.283-.074t.234-.177L8 16.629l3.439 3.869q.1.112.234.177t.283.074t.29-.04t.252-.148q.112-.1.177-.234t.074-.283t-.04-.29t-.148-.252L8.75 15.215V9.496l7-3.434V8.25q0 2.5 2.5 2.5t2.5-2.5v-2.5q0-2.5-2.5-2.5q-1.553 0-2.142.965L7.855 8.264q-.197.039-.348.171");
}

</style>
