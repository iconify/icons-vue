<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="p7kxi-b9w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:person-circle-off-20-regular" /></template>
<style>
.p7kxi-b9w {
  fill: currentColor;
  d: path("M2.146 2.146a.5.5 0 0 1 .708 0l15 15a.5.5 0 0 1-.707.707l-1.856-1.855a8 8 0 0 1-11.29-11.29L2.146 2.854a.5.5 0 0 1 0-.708M4.71 5.417a7 7 0 0 0 9.872 9.872l-1.472-1.472q-.15.16-.322.298C12.047 14.71 11.053 15 10 15s-2.047-.29-2.788-.885C6.459 13.511 6 12.616 6 11.5A1.5 1.5 0 0 1 7.5 10h1.793zM10 2a8 8 0 0 1 6.616 12.495l-.721-.722a7 7 0 0 0-9.669-9.669l-.722-.721A7.96 7.96 0 0 1 10 2m2.5 8a1.5 1.5 0 0 1 1.5 1.5q-.001.184-.019.36L12.121 10zM10 5a2 2 0 0 1 .903 3.782L8.217 6.096A2 2 0 0 1 10 5");
}

</style>
