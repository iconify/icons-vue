<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ru5lciblm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:view-comfy-rounded" /></template>
<style>
.ru5lciblm {
  fill: currentColor;
  d: path("M3.808 11.5q-.343 0-.576-.232T3 10.692V5.808q0-.343.232-.576T3.808 5h16.384q.343 0 .576.232t.232.576v4.884q0 .344-.232.576t-.576.232zm6.384 7.5q-.343 0-.575-.232t-.232-.576v-4.884q0-.344.232-.576t.575-.232h10q.344 0 .576.232t.232.576v4.884q0 .343-.232.576t-.576.232zm-6.384 0q-.343 0-.576-.232T3 18.192v-4.884q0-.344.232-.576t.576-.232h3.769q.343 0 .576.232q.231.232.231.576v4.884q0 .343-.232.576T7.578 19z");
}

</style>
