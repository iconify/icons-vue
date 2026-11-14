<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xyrknpbas"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:sms-delivered" /></template>
<style>
.xyrknpbas {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.028 16.356q-2.94-3.001-2.003-7.025q1-4.296 5.552-5.956q4.501-1.642 8.57.731q4.132 2.41 4.184 6.817q.053 4.408-4.023 6.895q-3.899 2.38-8.297.976l-5.255 1.911q-.14.051-.289.044t-.284-.069t-.236-.173t-.152-.251q-.03-.083-.04-.17t0-.175t.041-.171t.08-.156zM11 12.939L8.53 10.47q-.052-.053-.113-.094t-.13-.069t-.141-.043T8 10.25t-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.106.105-.163.243T7.25 11t.057.287t.163.243l3 3q.105.106.243.163t.287.057t.287-.057t.243-.163l5-5q.106-.105.163-.243T16.75 9t-.057-.287t-.163-.243q-.052-.053-.113-.094t-.13-.069t-.141-.043T16 8.25t-.146.014q-.073.015-.141.043t-.13.069t-.113.094z");
}

</style>
