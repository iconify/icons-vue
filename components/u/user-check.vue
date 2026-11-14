<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vjicb9bpp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:user-check" /></template>
<style>
.vjicb9bpp {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.818 5.068Q4.5 6.386 4.5 8.25t1.318 3.182T9 12.75t3.182-1.318T13.5 8.25t-1.318-3.182T9 3.75T5.818 5.068M17.5 11.689l-1.47-1.469q-.052-.053-.113-.094t-.13-.069t-.141-.043T15.5 10t-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146t.014.146q.015.073.043.141t.069.13t.094.113l2 2q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094l4-4q.106-.105.163-.243t.057-.287t-.057-.287t-.163-.243q-.052-.053-.113-.094t-.13-.069t-.141-.043T21.5 8t-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094zM1.75 20q0-2.427 2.213-4.015Q6.03 14.5 9 14.5t5.037 1.485Q16.25 17.573 16.25 20q0 1.75-1.75 1.75h-11q-1.75 0-1.75-1.75");
}

</style>
