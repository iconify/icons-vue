<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vxr4-0bhj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:voicemail-play" /></template>
<style>
.vxr4-0bhj {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 7.5q0-1.76 1.245-3.005T6 3.25t3.005 1.245T10.25 7.5q0 1.584-1.007 2.75h3.514Q11.75 9.084 11.75 7.5q0-1.76 1.245-3.005T16 3.25t3.005 1.245T20.25 7.5t-1.245 3.005T16 11.75H6q-1.76 0-3.005-1.245T1.75 7.5m16.321 7.04l1.351.732q1.179.638 1.179 1.978t-1.179 1.979l-1.351.731q-1.124.609-2.223-.045q-1.098-.655-1.098-1.933v-1.464q0-1.278 1.098-1.933q1.099-.654 2.223-.046zm-.714 1.319q-.375-.202-.741.016t-.366.644v1.464q0 .426.366.644t.741.016l1.351-.732q.393-.213.393-.66t-.393-.66z");
}

</style>
