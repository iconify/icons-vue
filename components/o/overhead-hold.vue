<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dqxmu7b_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:overhead-hold" /></template>
<style>
.dqxmu7b_u {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.25 1.75q2.5 0 2.5 2.5v1h8.5v-1q0-2.5 2.5-2.5t2.5 2.5v3.5q0 2.5-2.5 2.5t-2.5-2.5v-1h-8.5v1q0 2.5-2.5 2.5t-2.5-2.5v-3.5q0-1.036.732-1.768T5.25 1.75M12 9q-3.75 0-3.75 3.75T12 16.5t3.75-3.75T12 9M4.75 21.5q0-3.75 7.25-3.75t7.25 3.75q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146q0-2.25-5.75-2.25T6.25 21.5q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146");
}

</style>
