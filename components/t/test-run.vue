<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fzw6xci_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:test-run" /></template>
<style>
.fzw6xci_e {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m6.667 3.242l9.61 5.835q1.082.657 1.082 1.923t-1.082 1.923l-9.61 5.835q-1.125.683-2.271.037T3.25 16.834V5.166q0-1.315 1.146-1.961t2.271.037M15.28 17.47l1.47 1.469l3.72-3.719q.052-.053.113-.094t.13-.069t.141-.043T21 15t.146.014q.073.015.141.043t.13.069q.061.041.113.094q.106.105.163.243t.057.287t-.057.287t-.163.243l-4.25 4.25q-.052.053-.113.094t-.13.069t-.141.043t-.146.014q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094l-2-2q-.053-.052-.094-.113t-.069-.13t-.043-.141T14 18t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.105-.106.243-.163t.287-.057t.287.057t.243.163");
}

</style>
