<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t2jsi9rmt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:occupancy-sensor" /></template>
<style>
.t2jsi9rmt {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m2.701 8.886l7.75-6.119q1.549-1.222 3.098 0l7.75 6.119q.95.75.951 1.962v8.902q0 1.036-.732 1.768t-1.768.732H17q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146q0-5.25-5.75-5.25T6.25 21.5q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014H4.25q-1.036 0-1.768-.732T1.75 19.75v-8.902q.001-1.211.951-1.962M7 22.25q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146q0-3.75 4.25-3.75t4.25 3.75q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014zm5-13.5q-3.25 0-3.25 3.25T12 15.25T15.25 12T12 8.75");
}

</style>
