<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bxx0_v4je"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:terrain-slope-percent" /></template>
<style>
.bxx0_v4je {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5 2.25q-2.25 0-2.25 2.25T5 6.75T7.25 4.5T5 2.25m6.47.72l-8 8q-.106.105-.163.243t-.057.287t.057.287t.163.243q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094l8-8q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.105-.106-.243-.163T12 2.75t-.287.057t-.243.163M8.75 10.5q0-2.25 2.25-2.25q.932 0 1.591.659t.659 1.591t-.659 1.591T11 12.75q-2.25 0-2.25-2.25m-2.838 9.084q.448 1.666 2.173 1.666H20q2.25 0 2.25-2.25v-6.898q0-1.3-1.126-1.949q-1.127-.65-2.252.002L6.957 17.053q-1.493.865-1.045 2.531");
}

</style>
