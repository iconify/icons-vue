<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w9pfpybnw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:shot-medium" /></template>
<style>
.w9pfpybnw {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6 3.25h12q1.76 0 3.005 1.245T22.25 7.5v9q0 1.76-1.245 3.005T18 20.75h-.5q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146q0-5.5-6.25-5.5T5.75 20q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014H6q-1.76 0-3.005-1.245T1.75 16.5v-9q0-1.76 1.245-3.005T6 3.25m.5 17.5q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141T7.25 20q0-4 4.75-4t4.75 4q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014zM12 6.25q-3.5 0-3.5 3.5t3.5 3.5t3.5-3.5t-3.5-3.5");
}

</style>
