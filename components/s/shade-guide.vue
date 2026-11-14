<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gadj5lbsq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:shade-guide" /></template>
<style>
.gadj5lbsq {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.493 6.301q-.507-2.192-2.699-1.686T7.108 7.314l.416 1.803l-1.139-1.459q-1.386-1.771-3.158-.387q-1.772 1.385-.388 3.158l4.002 5.122q1.385 1.772 3.157.388q.315-.245.515-.555q.367.039.756-.05q.413-.096.731-.251q.318.155.731.251q.389.089.756.05q.2.31.515.555q1.772 1.384 3.157-.388l4.002-5.123q1.384-1.772-.388-3.157q-1.772-1.384-3.158.387l-1.139 1.459l.416-1.803q.506-2.192-1.686-2.699t-2.699 1.686L12 8.499zM9.75 18.5q0-2.25 2.25-2.25t2.25 2.25T12 20.75T9.75 18.5");
}

</style>
