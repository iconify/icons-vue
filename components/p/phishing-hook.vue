<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="s6ll8r_gt"/><path class="ix40ayy1e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:phishing-hook" /></template>
<style>
.ix40ayy1e {
  d: path("m14.25 15.25l3.5 2.75l3.5-2.75");
}

.s6ll8r_gt {
  d: path("M8.75 4.25a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0ZM10.5 6v9.5m-.019.376q-.017.172-.05.341t-.082.335q-.048.165-.111.326q-.064.16-.141.314q-.078.154-.17.3q-.091.146-.196.283t-.221.264q-.117.127-.245.243t-.266.219t-.285.193q-.146.091-.301.167T8.098 19q-.161.061-.327.108t-.336.079q-.169.031-.341.047t-.344.016q-.184 0-.368-.018q-.183-.018-.364-.054q-.18-.036-.357-.089q-.176-.054-.346-.124t-.333-.158q-.162-.087-.315-.189q-.154-.102-.296-.219t-.273-.247q-.13-.131-.247-.273t-.219-.296q-.102-.153-.189-.315q-.087-.163-.158-.333q-.07-.17-.124-.346q-.053-.177-.089-.357q-.036-.181-.054-.364Q3 15.684 3 15.5v-4l2.75 2.25m7.75.75H22V21h-8.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
