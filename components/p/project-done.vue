<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jl2eypb-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:project-done" /></template>
<style>
.jl2eypb-f {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5 4.25Q2.25 4.25 2.25 7v10q0 2.75 2.75 2.75h14q2.75 0 2.75-2.75V9q0-2.75-2.75-2.75h-7.189L10.03 4.47q-.105-.106-.243-.163T9.5 4.25zm6 9.939l3.97-3.969q.052-.053.113-.094t.13-.069t.141-.043T15.5 10t.146.014q.073.015.141.043t.13.069t.113.094q.106.105.163.243t.057.287t-.057.287t-.163.243l-4.5 4.5q-.052.053-.113.094t-.13.069t-.141.043T11 16t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094l-2.5-2.5q-.106-.105-.163-.243t-.057-.287t.057-.287t.163-.243q.052-.053.113-.094t.13-.069t.141-.043T8.5 12t.146.014q.073.015.141.043t.13.069t.113.094z");
}

</style>
