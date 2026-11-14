<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zq9ekhemz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:sail-mainsail" /></template>
<style>
.zq9ekhemz {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.469 1.915q7.65 6.12 11.511 14.335h.52q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014H6.75v3.75q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043T6 22.25t-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146v-19l.001-.033q.011-.245.163-.436q.094-.116.224-.188q.131-.072.279-.088q.041-.005.083-.005h.026q.121.005.234.047t.209.117zm.281 2.181V16.25h9.565Q12.935 9.408 6.75 4.096");
}

</style>
