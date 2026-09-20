<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wc08lcvdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:music-note-outline-rounded" /></template>
<style>
.wc08lcvdw {
  fill: currentColor;
  d: path("M7.935 18.93q-.877-.876-.877-2.122q0-1.247.881-2.124q.881-.876 2.119-.876q.575 0 1.091.204q.517.205.909.615V5q0-.343.234-.575t.581-.233h3.263q.347 0 .577.233t.23.575v.923q0 .343-.233.576q-.232.232-.576.232h-3.076v10.077q0 1.237-.877 2.118t-2.123.882q-1.247 0-2.124-.877");
}

</style>
