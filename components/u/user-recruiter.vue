<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="odatrzagm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:user-recruiter" /></template>
<style>
.odatrzagm {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.5 8.25q0-1.864 1.318-3.182T9 3.75t3.182 1.318T13.5 8.25t-1.318 3.182T9 12.75t-3.182-1.318T4.5 8.25m13.25-3q-4 0-4 4t4 4q1.149 0 2.065-.564l1.116 1.302q.048.056.106.102t.124.079t.137.053t.144.026t.147-.003t.144-.032t.135-.059t.12-.085q.113-.097.181-.23t.079-.281t-.035-.291q-.046-.142-.144-.255l-1.139-1.329q.82-1.047.82-2.433q0-1.657-1.172-2.828Q19.407 5.25 17.75 5.25M3.963 15.985Q1.75 17.573 1.75 20q0 1.75 1.75 1.75h11q1.75 0 1.75-1.75q0-2.427-2.213-4.015Q11.97 14.5 9 14.5t-5.037 1.485");
}

</style>
