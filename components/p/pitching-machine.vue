<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e58zpcfqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:pitching-machine" /></template>
<style>
.e58zpcfqi {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.007 4.757Q2.25 6.515 2.25 9t1.757 4.243q1.302 1.301 3.003 1.639l-3.657 6.239q-.037.063-.062.133q-.024.07-.034.143t-.006.147t.023.145t.051.138t.077.126t.1.108t.119.086q.128.075.276.096q.148.02.292-.017q.145-.038.264-.128t.194-.219l3.603-6.146l3.603 6.146q.075.129.194.219t.264.128q.144.037.292.017q.148-.021.276-.096q.064-.037.119-.086t.1-.108t.077-.126t.051-.138t.023-.145t-.006-.147t-.034-.143t-.062-.133L9.49 14.882q1.701-.338 3.003-1.639Q14.25 11.485 14.25 9t-1.757-4.243Q10.735 3 8.25 3T4.007 4.757M15.75 8.5q0-3.25 3.25-3.25t3.25 3.25T19 11.75T15.75 8.5m-7.5-2.25Q11 6.25 11 9t-2.75 2.75T5.5 9t2.75-2.75");
}

</style>
