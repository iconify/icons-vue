<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cw81syuef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:model" /></template>
<style>
.cw81syuef {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m13.247 2.353l6.5 3.742q.314.181.549.406q-.225-.013-.421.099l-5.802 3.348Q13.385 9.25 12 9.25t-2.073.698L4.125 6.6q-.196-.112-.421-.099q.235-.225.549-.406l6.5-3.742q1.247-.718 2.494 0m-3.948 8.964L3.375 7.9q-.196-.113-.297-.316Q3 7.9 3 8.262v7.476q0 1.446 1.253 2.167l6.5 3.742q.311.179.623.269q-.126-.189-.126-.416v-6.81q-2-.345-2-2.69q0-.366.049-.683m3.451 3.373v6.81q0 .227-.126.416q.312-.09.623-.269l6.5-3.742Q21 17.184 21 15.738V8.262q0-.362-.078-.678q-.101.203-.297.316l-5.924 3.417q.049.317.049.683q0 2.345-2 2.69");
}

</style>
