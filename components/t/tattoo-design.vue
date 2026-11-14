<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jokjejbkd"/><path class="s3xjj4bkp"/><path class="ej_aqbcss"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:tattoo-design" /></template>
<style>
.ej_aqbcss {
  d: path("m8.788 15.152l.06.06a.825.825 0 0 1-.384 1.384a.875.875 0 0 1-1.06-1.06a.825.825 0 0 1 1.384-.384M7.05 16.95l-1.768 1.768M3.25 20.75h.01");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jokjejbkd {
  d: path("m18.187 4.045l1.768 1.768a1.75 1.75 0 0 1 0 2.475l-2.828 2.828a1.75 1.75 0 0 1-2.475 0l-1.768-1.768a1.75 1.75 0 0 1 0-2.475l2.828-2.828a1.75 1.75 0 0 1 2.475 0");
}

.s3xjj4bkp {
  d: path("M13.768 10.232za1.5 1.5 0 0 1 0 2.122l-2.829 2.828a1.5 1.5 0 0 1-2.121 0a1.5 1.5 0 0 1 0-2.121l2.828-2.829a1.5 1.5 0 0 1 2.122 0");
}

</style>
