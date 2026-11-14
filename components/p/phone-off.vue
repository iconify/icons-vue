<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="igy4qi8vn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:phone-off" /></template>
<style>
.igy4qi8vn {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m4.03 2.97l17 17q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094l-17-17q-.053-.052-.094-.113t-.069-.13t-.043-.141T2.75 3.5t.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043q.072-.014.146-.014t.146.014q.073.015.141.043t.13.069t.113.094m7.464 5.695L5.578 2.75H8.5q1.743 0 2.225 1.807l.753 3.011l.007.035q.115.575.009 1.062M7.47 16.53q4.69 4.691 10.951 4.72L2.75 5.579q.029 6.261 4.72 10.951m13.78 1.892l-5.915-5.916q.487-.106 1.062.009l.035.007l3 .75q1.818.485 1.818 2.228z");
}

</style>
