<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ev4dyabsk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:skillet-cooktop-rounded" /></template>
<style>
.ev4dyabsk {
  fill: currentColor;
  d: path("M6 14.346q-.846 0-1.423-.577T4 12.346V9.5q0-.213.143-.357T4.5 9h11.506q.028-.748.473-1.35t1.167-.838l3.733-1.264q.188-.067.371.03q.183.099.25.288t-.024.37t-.28.25L17.963 7.75q-.434.139-.699.516q-.264.378-.264.838v3.242q0 .827-.577 1.413T15 14.346zm4 5.154v-1.77q0-.268-.173-.441q-.173-.174-.442-.174H3.5q-.213 0-.357-.143Q3 16.829 3 16.615q0-.213.143-.356t.357-.144h5.885q.67 0 1.143.473q.472.471.472 1.143V19.5q0 .214-.143.357T10.5 20t-.357-.143T10 19.5m3 0v-1.77q0-.67.472-1.142t1.144-.472H20.5q.214 0 .357.143t.143.356t-.143.357t-.357.144h-5.884q-.27 0-.443.173q-.173.172-.173.442V19.5q0 .214-.143.357T13.5 20t-.357-.143T13 19.5");
}

</style>
