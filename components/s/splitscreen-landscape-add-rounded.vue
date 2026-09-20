<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q-pcs47tv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:splitscreen-landscape-add-rounded" /></template>
<style>
.q-pcs47tv {
  fill: currentColor;
  d: path("M19.913 7.856q-.144-.143-.144-.356V6h-1.5q-.212 0-.356-.144t-.144-.357t.144-.356t.356-.143h1.5V3.5q0-.213.144-.356Q20.057 3 20.27 3t.356.144t.143.356V5h1.5q.213 0 .357.144t.143.357t-.143.356t-.357.143h-1.5v1.5q0 .213-.144.356T20.27 8t-.356-.144m-12.72 7.76H10q.343 0 .576-.233t.232-.575V9.192q0-.343-.232-.575T10 8.385H7.192q-.343 0-.575.232t-.232.575v5.616q0 .343.232.575t.575.233M4.615 19q-.666 0-1.14-.475T3 17.386V6.615q0-.666.475-1.14T4.615 5H14.8q.248 0 .42.18t.164.447q.008.76.252 1.457q.243.697.691 1.3H14q-.343 0-.575.233t-.233.575v5.616q0 .343.232.575t.576.233h2.808q.343 0 .575-.233t.233-.575V9.575q.609.402 1.297.595t1.425.192q.273.002.468.163t.194.416v6.444q0 .666-.475 1.14t-1.14.475z");
}

</style>
