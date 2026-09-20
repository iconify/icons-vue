<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nnq4t7dxd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:work-history-outline-rounded" /></template>
<style>
.nnq4t7dxd {
  fill: currentColor;
  d: path("M4 19V8zm.616 1q-.691 0-1.153-.462T3 18.384V8.616q0-.691.463-1.153T4.615 7H9V5.615q0-.69.463-1.153T10.616 4h2.769q.69 0 1.153.462T15 5.615V7h4.385q.69 0 1.152.463T21 8.616v3.519q0 .213-.143.344t-.357.13t-.357-.143T20 12.11V8.616q0-.27-.173-.443T19.385 8H4.615q-.269 0-.442.173T4 8.616v9.769q0 .269.173.442t.443.173h7.192q.213 0 .357.143t.143.357t-.143.357t-.357.143zM10 7h4V5.615q0-.269-.173-.442T13.385 5h-2.77q-.269 0-.442.173T10 5.615zm5.165 13.836Q14 19.67 14 18t1.165-2.835T18 14t2.836 1.165T22 18t-1.164 2.836T18 22t-2.835-1.164m3.22-2.997V15.5q0-.161-.112-.273T18 15.116t-.273.111t-.111.273v2.333q0 .161.055.3q.056.14.187.27l1.519 1.52q.112.112.264.121q.151.01.282-.121t.13-.273t-.13-.273z");
}

</style>
