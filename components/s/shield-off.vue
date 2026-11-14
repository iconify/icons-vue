<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zhbphqbkg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:shield-off" /></template>
<style>
.zhbphqbkg {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19.156 16.327L6.717 3.888l5.025-1.842Q11.867 2 12 2t.258.046l7.5 2.75q.108.04.2.11q.091.07.157.165q.066.094.1.204q.035.11.035.225v6q0 2.695-1.094 4.827M4.03 2.97l17 17q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094l-17-17q-.053-.052-.094-.113t-.069-.13t-.043-.141T2.75 3.5t.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043q.072-.014.146-.014t.146.014q.073.015.141.043t.13.069t.113.094m8.247 18.977q2.594-1.032 4.344-2.498L3.75 6.578V11.5q0 7.276 7.973 10.447q.133.053.277.053t.277-.053");
}

</style>
