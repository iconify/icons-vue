<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vq76arbdy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:tile-large-rounded" /></template>
<style>
.vq76arbdy {
  fill: currentColor;
  d: path("M4 19.192v-3.134q0-.344.232-.576t.576-.232h4.994q.354 0 .584.232t.23.576v3.134q0 .343-.233.576T9.808 20H4.813q-.353 0-.583-.232T4 19.192m9.366 0v-3.134q0-.344.232-.576t.575-.232h5.012q.356 0 .585.232t.23.576v3.134q0 .343-.232.576t-.576.232H14.18q-.355 0-.585-.232t-.23-.576M4 11.692V4.808q0-.343.232-.576T4.808 4h14.384q.344 0 .576.232t.232.576v6.884q0 .344-.232.576t-.576.232H4.808q-.343 0-.576-.232T4 11.692");
}

</style>
