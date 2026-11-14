<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q-91t7bls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:route-one-way-trip" /></template>
<style>
.q-91t7bls {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m20.53 3.97l-2.5-2.5q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014t-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.106.105-.163.243T16.75 2t.057.287t.163.243l1.219 1.22H9q-1.76 0-3.005 1.245T4.75 8t1.245 3.005T9 12.25h6q2.75 0 2.75 2.75q0 1.139-.805 1.945q-.806.805-1.945.805H8.701q-.351-2.5-3.201-2.5q-3.25 0-3.25 3.25t3.25 3.25q2.85 0 3.201-2.5H15q1.76 0 3.005-1.245T19.25 15t-1.245-3.005T15 10.75H9q-2.75 0-2.75-2.75T9 5.25h9.189L16.97 6.47q-.106.105-.163.243T16.75 7t.057.287t.163.243q.052.053.113.094t.13.069t.141.043t.146.014q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094l2.5-2.5q.106-.105.163-.243t.057-.287t-.057-.287t-.163-.243");
}

</style>
