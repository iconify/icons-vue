<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tm4v5_37a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:vpn-key-alert-rounded" /></template>
<style>
.tm4v5_37a {
  fill: currentColor;
  d: path("M7 13.23q.508 0 .87-.36t.36-.87t-.36-.87t-.87-.36t-.87.36t-.36.87t.36.87t.87.36M7 17q-2.083 0-3.542-1.457T2 12.005T3.458 8.46Q4.917 7 7 7q1.833 0 3.134 1.09q1.3 1.089 1.708 2.68h5.581q.343 0 .576.23t.232.571v4.813q0 .262-.182.439t-.433.177t-.434-.177t-.182-.438V13.23h-5.158q-.408 1.59-1.708 2.68T7 17m13.441.02q-.21-.209-.21-.52t.21-.52t.52-.21t.52.21q.211.209.211.52t-.21.52t-.52.21t-.52-.21m.163-2.856q-.144-.144-.144-.356V10.5q0-.213.145-.356t.356-.144t.356.144t.144.356v3.308q0 .212-.144.356t-.357.144t-.356-.144");
}

</style>
