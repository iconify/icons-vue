<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="osrg-kb_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:puck" /></template>
<style>
.osrg-kb_x {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.25 8.999v5.5q.002 2.144 3.083 3.513Q8.114 19.249 12 19.249t6.667-1.236q3.081-1.369 3.083-3.512V8.999q.002-2.143-3.08-3.514Q15.888 4.249 12 4.249T5.33 5.485q-3.081 1.37-3.08 3.514m3.08 3.516q2.782 1.236 6.67 1.236t6.67-1.236q.93-.414 1.58-.899v2.883q-.001 1.17-2.192 2.143q-2.49 1.107-6.058 1.107t-6.058-1.107Q3.751 15.669 3.75 14.5v-2.884q.65.485 1.58.899");
}

</style>
