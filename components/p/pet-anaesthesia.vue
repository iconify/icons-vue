<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sg1g54bux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:pet-anaesthesia" /></template>
<style>
.sg1g54bux {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.001 3.25q.841 0 1.399.652l5.456 2.938q.089.048.162.118t.126.157q.052.088.079.186q.027.097.027.199v.75H14q2.936 0 4.843 1.907T20.75 15t-1.907 4.843T14 21.75q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T13.25 21t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014q5.25 0 5.25-5.25T14 9.75h-1.75v.75q0 .102-.027.199t-.079.186q-.052.087-.126.157q-.073.07-.162.118L6.4 14.098q-.558.652-1.4.652q-1.257 0-1.945-1.967Q2.5 11.199 2.5 9q0-5.749 2.499-5.75zm5.749 4.698l-3.473-1.87Q7.5 7.282 7.5 9t-.223 2.922l3.473-1.87z");
}

</style>
