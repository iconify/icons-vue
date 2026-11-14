<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g67afbcop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:pill-round" /></template>
<style>
.g67afbcop {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.25 9.999v4q.002 2.144 3.083 3.513Q8.114 18.749 12 18.749t6.667-1.236q3.081-1.369 3.083-3.512V9.999q.002-2.143-3.08-3.514Q15.888 5.249 12 5.249T5.33 6.485q-3.081 1.37-3.08 3.514m3.08 3.516q2.782 1.236 6.67 1.236t6.67-1.236q.93-.414 1.58-.899v1.383q-.001 1.17-2.192 2.143q-2.49 1.107-6.058 1.107t-6.058-1.107Q3.751 15.169 3.75 14v-1.384q.65.485 1.58.899");
}

</style>
