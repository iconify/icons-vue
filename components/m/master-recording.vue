<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uc5105v-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:master-recording" /></template>
<style>
.uc5105v-e {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.25 11.5q-.001-4.039 2.855-6.896T12 1.747t6.895 2.857T21.75 11.5q.001 4.039-2.855 6.896q-.784.785-1.658 1.354H21.5q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-9.235q-.132.003-.265.003q-4.04 0-6.895-2.857Q2.249 15.539 2.25 11.5M9.5 7.25q0 2.5 2.5 2.5q1.036 0 1.768-.732T14.5 7.25t-.732-1.768T12 4.75q-2.5 0-2.5 2.5m-1.25 4q-2.5 0-2.5 2.5t2.5 2.5t2.5-2.5t-2.5-2.5m5 2.5q0 2.5 2.5 2.5t2.5-2.5t-2.5-2.5t-2.5 2.5");
}

</style>
