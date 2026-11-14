<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rjoof_boc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:pet-love" /></template>
<style>
.rjoof_boc {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m3.47 13.53l8 8q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094l8-8q2.352-2.351 1.512-5.831q-.915-3.79-4.959-4.194q-3.151-.35-5.083 2.142q-1.931-2.493-5.075-2.143q-4.052.405-4.967 4.195q-.84 3.48 1.512 5.831M7.75 13V9.75q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043T8.5 9q.215 0 .397.114l1.818 1.136h2.57l1.818-1.136q.126-.079.273-.104t.293.009t.266.12q.122.087.201.214q.114.182.114.397V13q0 3.75-4.25 3.75T7.75 13");
}

</style>
