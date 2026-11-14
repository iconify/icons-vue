<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n2zhfls7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:oval" /></template>
<style>
.n2zhfls7m {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 12q0-3.088 3.109-5.215Q7.833 4.75 12 4.75t7.141 2.035Q22.25 8.912 22.25 12t-3.109 5.215Q16.167 19.25 12 19.25t-7.141-2.035Q1.75 15.088 1.75 12");
}

</style>
