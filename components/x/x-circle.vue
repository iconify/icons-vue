<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p1k8cqb2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:x-circle" /></template>
<style>
.p1k8cqb2o {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 12q0-4.246 3.002-7.248T12 1.75t7.248 3.002T22.25 12t-3.002 7.248T12 22.25t-7.248-3.002T1.75 12m11.311 0l2.469-2.47q.053-.052.094-.113t.069-.13t.043-.141T15.75 9t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.105-.106-.243-.163T15 8.25t-.287.057t-.243.163L12 10.939L9.53 8.47q-.105-.106-.243-.163T9 8.25t-.287.057t-.243.163t-.163.243Q8.25 8.851 8.25 9t.057.287t.163.243L10.939 12L8.47 14.47q-.106.105-.163.243T8.25 15t.057.287t.163.243q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094L12 13.061l2.47 2.469q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113z");
}

</style>
