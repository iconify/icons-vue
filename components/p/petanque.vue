<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bfz12bbup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:petanque" /></template>
<style>
.bfz12bbup {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.818 3.818Q7.5 5.136 7.5 7t1.318 3.182T12 11.5t3.182-1.318T16.5 7t-1.318-3.182T12 2.5T8.818 3.818m10.942.432h-.01q-.074 0-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141T19 5t.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h.01q.074 0 .146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141q.014-.072.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014M3.318 12.818Q2 14.136 2 16t1.318 3.182T6.5 20.5t3.182-1.318T11 16t-1.318-3.182T6.5 11.5t-3.182 1.318M13 16q0-1.864 1.318-3.182T17.5 11.5t3.182 1.318T22 16t-1.318 3.182T17.5 20.5t-3.182-1.318T13 16");
}

</style>
