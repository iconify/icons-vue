<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n4uppwbcw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:user-attributes-rounded" /></template>
<style>
.n4uppwbcw {
  fill: currentColor;
  d: path("M14.866 6.73q-.213 0-.357-.143q-.143-.144-.143-.357t.143-.356t.357-.143h6q.212 0 .356.144t.143.357t-.143.356t-.357.143zm0 3.77q-.213 0-.357-.144t-.143-.357t.143-.356t.357-.143h6q.212 0 .356.144t.143.357t-.143.356t-.357.143zm0 3.77q-.213 0-.357-.145t-.143-.357t.143-.356t.357-.143h6q.212 0 .356.144q.143.144.143.357t-.143.356t-.357.143zm-8.577-1.304q-.654-.65-.654-1.577q0-.928.649-1.581q.65-.654 1.577-.654q.928 0 1.581.65q.654.648.654 1.576t-.65 1.581q-.648.654-1.576.654t-1.581-.649m-3.654 5.073v-.324q0-.326.163-.622t.44-.474q1.049-.598 2.196-.916t2.432-.319t2.431.319q1.147.318 2.195.916q.277.179.44.474t.164.622v.323q0 .344-.232.576t-.575.232H3.442q-.343 0-.575-.232t-.233-.576");
}

</style>
