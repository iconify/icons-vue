<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kk7g02nkx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:shapes" /></template>
<style>
.kk7g02nkx {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.25 8.5q0-2.589 1.831-4.419Q5.911 2.25 8.5 2.25t4.419 1.831T14.75 8.5H14q-2.278 0-3.889 1.611T8.5 14v.75q-2.589 0-4.419-1.831Q2.25 11.089 2.25 8.5M14 9.75h3.5q1.76 0 3.005 1.245T21.75 14v3.5q0 1.76-1.245 3.005T17.5 21.75H14q-1.76 0-3.005-1.245T9.75 17.5V14q0-1.76 1.245-3.005T14 9.75m0 1.5q-2.75 0-2.75 2.75v3.5q0 2.75 2.75 2.75h3.5q2.75 0 2.75-2.75V14q0-2.75-2.75-2.75zm-1.327 1.905q.163-.319.482-.482q-.114.125-.236.246q-.121.122-.246.236");
}

</style>
