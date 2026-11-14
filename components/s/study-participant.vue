<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nintkyb3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:study-participant" /></template>
<style>
.nintkyb3o {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.75 6.5q0-1.76 1.245-3.005T12 2.25t3.005 1.245T16.25 6.5t-1.245 3.005T12 10.75T8.995 9.505T7.75 6.5m-3.5 11v4q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-4q0-1.553 1.098-2.652Q7.947 13.75 9.5 13.75h5q3.75 0 3.75 3.75v4q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-4q0-2.175-1.538-3.712q-1.537-1.538-3.712-1.538h-5q-2.175 0-3.712 1.538Q4.25 15.325 4.25 17.5m7-2.25h1.5q1.036 0 1.768.732t.732 1.768v.5q0 1.036-.732 1.768t-1.768.732h-1.5q-2.5 0-2.5-2.5v-.5q0-2.5 2.5-2.5");
}

</style>
