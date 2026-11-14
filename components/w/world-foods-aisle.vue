<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ovb8vwg_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:world-foods-aisle" /></template>
<style>
.ovb8vwg_z {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10.891 10.25h1.855l8.298-6.346q.119-.09.263-.129q.144-.038.292-.018q.148.019.277.094t.22.193q.045.059.077.125q.033.067.052.138t.023.145t-.005.147t-.033.143t-.061.134t-.086.119q-.049.056-.107.101l-6.741 5.154H21q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q-.001 4.038-2.857 6.892q-2.855 2.855-6.893 2.855t-6.893-2.855Q2.251 15.038 2.25 11q0-.074.014-.146q.015-.073.043-.141t.069-.129t.093-.114t.114-.093q.062-.042.13-.07t.14-.043T3 10.25h5.703l8.283-7.796q.109-.102.248-.155q.14-.053.289-.049q.149.005.285.066t.238.17q.051.054.09.116t.065.132t.039.142q.012.073.01.147q-.003.074-.019.146q-.017.072-.047.139t-.073.127t-.097.111z");
}

</style>
