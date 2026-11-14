<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j3-5_kb3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:results-loss" /></template>
<style>
.j3-5_kb3e {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 12q0-4.246 3.002-7.248T12 1.75t7.248 3.002T22.25 12t-3.002 7.248T12 22.25t-7.248-3.002T1.75 12m11.311 0l2.969-2.97q.106-.105.163-.243t.057-.287t-.057-.287t-.163-.243q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014t-.146.014q-.073.015-.141.043t-.13.069t-.113.094L12 10.939L9.03 7.97q-.105-.106-.243-.163T8.5 7.75t-.287.057t-.243.163t-.163.243t-.057.287t.057.287t.163.243L10.939 12L7.97 14.97q-.053.052-.094.113t-.069.13t-.043.141t-.014.146t.014.146q.015.073.043.141t.069.13t.094.113q.105.106.243.163t.287.057t.287-.057t.243-.163L12 13.061l2.97 2.969q.105.106.243.163t.287.057t.287-.057t.243-.163q.106-.105.163-.243t.057-.287t-.057-.287t-.163-.243z");
}

</style>
