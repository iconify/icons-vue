<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xps2i7bzs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:user-attributes-outline" /></template>
<style>
.xps2i7bzs {
  fill: currentColor;
  d: path("M14.366 6.73v-1h7v1zm0 3.77v-1h7v1zm0 3.77v-1h7v1zm-8.077-1.304q-.654-.65-.654-1.577q0-.928.649-1.581q.65-.654 1.577-.654q.928 0 1.581.65q.654.648.654 1.576t-.65 1.581q-.648.654-1.576.654t-1.581-.649m-3.654 5.88v-1.13q0-.327.163-.622t.44-.475q1.049-.598 2.196-.916t2.432-.318t2.431.318t2.195.916q.277.179.44.475t.164.622v1.13zm1.034-1.307v.307h8.393v-.307q-.99-.558-2.052-.856t-2.144-.298t-2.145.298q-1.061.298-2.052.856m5.063-5.288q.364-.364.364-.866t-.364-.867t-.866-.364t-.867.364t-.364.867t.364.866t.867.365q.501 0 .866-.365m-.866 5.595");
}

</style>
