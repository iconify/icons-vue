<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h4vaejbbs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:patient-list-outline-sharp" /></template>
<style>
.h4vaejbbs {
  fill: currentColor;
  d: path("M14.289 12.966q-.655-.65-.655-1.577t.65-1.581t1.577-.654t1.581.65t.654 1.576t-.65 1.582t-1.576.654t-1.581-.65m-3.654 5.88v-1.13q0-.327.163-.622t.44-.475q1.049-.598 2.196-.916t2.432-.318q1.284 0 2.431.318t2.195.916q.277.179.44.475t.164.622v1.13zm1.034-1.307v.307h8.393v-.307q-.99-.558-2.052-.856t-2.144-.298q-1.083 0-2.145.298q-1.061.298-2.052.856m5.063-5.288q.364-.364.364-.866t-.364-.867t-.866-.364t-.867.364t-.364.867t.364.866t.867.365q.501 0 .866-.365M3.885 13.5v-1h7v1zm0-8v-1h11v1zm7.811 4H3.885v-1h8.384q-.177.233-.322.473t-.25.527");
}

</style>
