<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v_08g-gfq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:shift-lock-rounded" /></template>
<style>
.v_08g-gfq {
  fill: currentColor;
  d: path("M9 15.808v-3.039H6.744q-.505 0-.74-.447q-.233-.447.071-.85L11.36 4.45q.249-.336.644-.336q.394 0 .637.336l5.284 7.021q.304.404.07.851t-.739.447H15v3.039q0 .343-.232.575t-.576.233H9.808q-.343 0-.576-.233T9 15.808M5.5 20q-.213 0-.356-.144T5 19.499t.144-.356T5.5 19h13q.213 0 .356.144t.144.357t-.144.356T18.5 20z");
}

</style>
