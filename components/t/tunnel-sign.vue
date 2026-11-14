<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tuh7accfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:tunnel-sign" /></template>
<style>
.tuh7accfv {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 20.293V12q0-4.246 3.002-7.248T12 1.75t7.248 3.002T22.25 12v8.293q.11.039.202.109t.16.165t.103.206t.035.227q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014H2q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T1.25 21q0-.116.035-.227t.103-.206q.067-.095.16-.165q.092-.07.202-.109m6-.043h8.5V14.5q0-1.76-1.245-3.005T12 10.25t-3.005 1.245T7.75 14.5zm10 0h3V12q0-3.624-2.563-6.187T12 3.25T5.813 5.813T3.25 12v8.25h3V14.5q0-2.382 1.684-4.066T12 8.75t4.066 1.684T17.75 14.5z");
}

</style>
