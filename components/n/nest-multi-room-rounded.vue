<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xbgu2xb-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:nest-multi-room-rounded" /></template>
<style>
.xbgu2xb-d {
  fill: currentColor;
  d: path("M5.808 20q-.343 0-.576-.232T5 19.192v-2.634q0-.344.232-.576t.576-.232h6.884q.343 0 .576.232t.232.576v2.634q0 .343-.232.576t-.576.232zm9.5 0q-.343 0-.576-.232t-.232-.576v-2.634q0-.33.24-.569q.239-.239.568-.239h2.884q.344 0 .576.232t.232.576v2.634q0 .343-.232.576t-.576.232zm-9.5-5.25q-.343 0-.576-.232T5 13.942v-2.634q0-.343.232-.576t.576-.232h2.884q.343 0 .576.232t.232.576v2.634q0 .344-.232.576t-.576.232zm5.5 0q-.343 0-.576-.232t-.232-.576v-2.634q0-.343.232-.576t.576-.232h6.884q.344 0 .576.232t.232.576v2.634q0 .344-.232.576t-.576.232zM6.212 9.5q-.293 0-.376-.27t.133-.457l5.062-3.815q.223-.162.466-.243t.507-.08t.504.08t.461.243l5.062 3.815q.217.187.134.457q-.084.27-.377.27z");
}

</style>
