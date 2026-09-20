<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="adztw06jy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:patient-list-rounded" /></template>
<style>
.adztw06jy {
  fill: currentColor;
  d: path("M14.289 12.966q-.655-.65-.655-1.577t.65-1.581t1.577-.654t1.581.65t.654 1.576t-.65 1.582t-1.576.654t-1.581-.65m-2.847 5.88q-.343 0-.575-.232t-.232-.575v-.324q0-.326.163-.622t.44-.474q1.049-.598 2.196-.916t2.432-.319q1.284 0 2.431.319q1.147.318 2.195.916q.277.179.44.474t.164.622v.323q0 .344-.232.576t-.575.232zM10.385 13.5h-6q-.213 0-.357-.144t-.143-.357t.143-.356t.357-.143h6q.212 0 .356.144t.144.357t-.144.356t-.356.143m4-8h-10q-.213 0-.357-.144t-.143-.357t.143-.356t.357-.143h10q.212 0 .356.144t.144.357t-.144.356t-.356.143m-2.689 4H4.385q-.213 0-.357-.144t-.143-.357t.143-.356t.357-.143h7.884q-.177.233-.322.473t-.25.527");
}

</style>
