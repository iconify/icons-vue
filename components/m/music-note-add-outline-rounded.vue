<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rrg617awy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:music-note-add-outline-rounded" /></template>
<style>
.rrg617awy {
  fill: currentColor;
  d: path("M9.992 18.93q-.877-.876-.877-2.122q0-1.247.882-2.124q.881-.876 2.119-.876q.575 0 1.09.204t.91.615V5q0-.343.234-.575t.581-.233h3.263q.347 0 .576.233T19 5v.923q0 .343-.232.576t-.576.232h-3.076v10.077q0 1.237-.877 2.118t-2.124.882t-2.123-.877M7.231 8.192h-2.5q-.213 0-.356-.144q-.144-.144-.144-.356q0-.213.144-.357t.356-.143h2.5v-2.5q0-.212.144-.356t.357-.144t.356.144t.143.356v2.5h2.5q.212 0 .356.144t.144.357t-.144.356t-.356.143h-2.5v2.5q0 .213-.144.356q-.144.144-.357.144t-.356-.144t-.143-.356z");
}

</style>
