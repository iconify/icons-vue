<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c14h-_bbz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:monitor-weight-loss-outline-rounded" /></template>
<style>
.c14h-_bbz {
  fill: currentColor;
  d: path("M16 19.5q-.213 0-.356-.144t-.144-.357t.144-.356T16 18.5h6q.213 0 .356.144t.144.357t-.144.356T22 19.5zM5 19V5zm6.996-12.615q-1.092 0-1.852.764t-.76 1.856t.765 1.85t1.856.76t1.85-.764t.76-1.856t-.764-1.85t-1.856-.76M10.85 8.65Q11 8.8 11 9t-.15.35t-.35.15t-.35-.15T10 9t.15-.35t.35-.15t.35.15m1.5 0q.15.15.15.35t-.15.35t-.35.15t-.35-.15T11.5 9t.15-.35t.35-.15t.35.15m1.5 0Q14 8.8 14 9t-.15.35t-.35.15t-.35-.15T13 9t.15-.35t.35-.15t.35.15M5.616 20q-.691 0-1.153-.462T4 18.384V5.616q0-.691.463-1.153T5.616 4h12.769q.69 0 1.153.463T20 5.616v7q0 .212-.144.356t-.357.144t-.356-.144t-.143-.356v-7q0-.231-.192-.424T18.384 5H5.616q-.231 0-.424.192T5 5.616v12.769q0 .23.192.423t.423.192h7.25q.213 0 .357.144t.144.357t-.144.356t-.356.143z");
}

</style>
