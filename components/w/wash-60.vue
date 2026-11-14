<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="txeqv2bnv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:wash-60" /></template>
<style>
.txeqv2bnv {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.998 6.439q-2.748-2.442-5.496 0q-.073.065-.127.147t-.086.174t-.037.19q-.007.098.012.194l2.25 11.5q.012.064.036.124t.056.116q.033.056.075.105t.092.09t.107.073q.056.032.117.054t.124.033t.129.011h13.5q.065 0 .129-.011q.063-.011.124-.033t.117-.054t.107-.073t.092-.09q.042-.049.075-.105t.056-.116t.036-.124l2.25-11.5q.017-.085.013-.172q-.003-.086-.026-.17q-.022-.083-.064-.159q-.041-.077-.098-.141q-.1-.112-.234-.177t-.283-.074q-.149-.008-.29.04q-.141.049-.252.148q-1.752 1.558-3.504 0q-2.748-2.442-5.496 0q-1.752 1.558-3.504 0M5.75 12.5q0-1.75 1.75-1.75t1.75 1.75t-1.75 1.75t-1.75-1.75M12 10.75q1.75 0 1.75 1.75T12 14.25t-1.75-1.75T12 10.75m2.75 1.75q0-1.75 1.75-1.75t1.75 1.75t-1.75 1.75t-1.75-1.75");
}

</style>
