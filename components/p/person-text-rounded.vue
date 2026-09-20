<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a237lwb_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:person-text-rounded" /></template>
<style>
.a237lwb_s {
  fill: currentColor;
  d: path("M17.346 16.885q-.212 0-.356-.144t-.144-.357t.144-.356t.356-.144H20.5q.213 0 .356.145t.144.356t-.144.356t-.356.144zm-2-4.385q-.212 0-.356-.144t-.144-.357t.144-.356t.356-.143H20.5q.213 0 .356.144t.144.357t-.144.356t-.356.143zm-2-4.384q-.212 0-.356-.144t-.144-.357t.144-.356t.356-.143H20.5q.213 0 .356.143q.144.144.144.357t-.144.356t-.356.144zm-6.692 2.812Q6 10.278 6 9.35t.65-1.582q.649-.654 1.576-.654t1.582.65t.654 1.577t-.65 1.581t-1.577.654t-1.581-.65m-2.846 5.958q-.343 0-.576-.233Q3 16.42 3 16.078v-.516q0-.326.164-.621q.163-.296.44-.475q1.048-.598 2.195-.916t2.432-.318t2.432.318t2.195.917q.277.178.44.474q.164.295.164.621v.516q0 .343-.233.575q-.232.232-.575.232z");
}

</style>
