<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zd8zt3bzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:shoplifting" /></template>
<style>
.zd8zt3bzx {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 6q0-3.25 4.25-3.25h12q4.25 0 4.25 3.25v1.5q0 4.75-5.25 4.75q-1.64 0-3.577-1.32q-.999-.68-1.423-.68t-1.423.68Q8.64 12.25 7 12.25q-5.25 0-5.25-4.75zM5.5 7.25Q5.5 8 7 8t1.5-.75T7 6.5t-1.5.75m10 .001q.002.748 1.5.748q1.499 0 1.5-.75q-.001-.748-1.5-.748q-1.498 0-1.5.748zM13.75 17q0-2.25 2.25-2.25h4q2.25 0 2.25 2.25v3q0 2.25-2.25 2.25h-4q-2.25 0-2.25-2.25zm2.25-.75h1.25V17h-2q0-.75.75-.75m2.75 0V17h2q0-.75-.75-.75zm-3.5 2.25h5.5V20q0 .75-.75.75h-4q-.75 0-.75-.75z");
}

</style>
