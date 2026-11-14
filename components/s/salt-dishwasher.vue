<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x3rd79byy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:salt-dishwasher" /></template>
<style>
.x3rd79byy {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.75 2.25h6.5q1.036 0 1.768.732t.732 1.768v2q0 1.036-.732 1.768l-.03.029q.269.199.517.448Q16.75 10.24 16.75 12v.765l-2.648 3.852q-.109.158-.185.334q-1.08 2.477.4 4.737l.085.127q-.861.435-1.902.435h-5q-1.76 0-3.005-1.245T3.25 18v-6q0-1.76 1.245-3.005q.192-.192.396-.354q-.641-.625-.641-1.891v-2q0-2.5 2.5-2.5m12.368 11.075l2.75 4q.041.059.07.125q.809 1.858-.301 3.554T18.5 22.699t-3.137-1.695t-.3-3.554q.028-.066.069-.125l2.75-4q.084-.123.21-.204q.125-.081.271-.108q.147-.028.293.003t.269.116q.114.079.193.193m-2.707 4.787q-.441 1.081.207 2.07q.666 1.017 1.882 1.017t1.882-1.017q.648-.989.207-2.07L18.5 15.074z");
}

</style>
