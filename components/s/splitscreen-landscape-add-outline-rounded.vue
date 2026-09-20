<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j3td8ybut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:splitscreen-landscape-add-outline-rounded" /></template>
<style>
.j3td8ybut {
  fill: currentColor;
  d: path("M14 15.616h2.808q.343 0 .575-.233t.233-.575V9.192q0-.343-.233-.575t-.575-.233H14q-.343 0-.575.233t-.233.575v5.616q0 .343.232.575t.576.233m-6.808 0H10q.343 0 .576-.233t.232-.575V9.192q0-.343-.232-.575T10 8.385H7.192q-.343 0-.575.232t-.232.575v5.616q0 .343.232.575t.575.233M19.77 6h-1.5q-.212 0-.356-.144t-.144-.357t.144-.356T18.27 5h1.5V3.5q0-.213.144-.356Q20.057 3 20.27 3t.356.144t.143.356V5h1.5q.213 0 .357.144t.143.357t-.143.356t-.357.143h-1.5v1.5q0 .213-.144.356T20.27 8t-.356-.144t-.144-.356zM4 18V6zm.616 1q-.691 0-1.153-.462T3 17.384V6.616q0-.691.463-1.153T4.615 5h10.27q.212 0 .356.144t.143.357t-.143.356t-.357.143H4.616q-.231 0-.424.192T4 6.616v10.769q0 .23.192.423t.423.192h14.77q.23 0 .423-.192t.192-.423v-6.5q0-.213.144-.357t.357-.143t.356.143t.143.357v6.5q0 .69-.462 1.153T19.385 19z");
}

</style>
