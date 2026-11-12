<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="g8yt8qbkp"/><path class="c4cyhmtxp"/><path class="fjrd2nfzd"/><path class="ij4w06bdg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:paint-bucket-linear" /></template>
<style>
.c4cyhmtxp {
  d: path("M1.9082 13.9114H17.7222");
}

.fjrd2nfzd {
  d: path("M22.0923 19.0649C22.0923 20.1555 21.2435 21.0396 20.1965 21.0396C19.1495 21.0396 18.3008 20.1555 18.3008 19.0649C18.3008 18.3825 19.0429 17.4717 19.5985 16.8855C19.9274 16.5385 20.4656 16.5385 20.7945 16.8855C21.3501 17.4717 22.0923 18.3825 22.0923 19.0649Z");
}

.g8yt8qbkp {
  d: path("M13.7271 8.91138L2.72705 5.41138");
}

.ij4w06bdg {
  stroke-linejoin: round;
  d: path("M11.0092 3.61173L4.68406 9.93658L4.68406 9.93659C2.83317 11.7875 1.90771 12.7129 1.90771 13.8629C1.90771 15.0126 2.83254 15.9375 4.68248 17.7874L5.33831 18.4432L5.33832 18.4432C7.18915 20.2941 8.11467 21.2196 9.26465 21.2196C10.4146 21.2196 11.3402 20.2941 13.191 18.4432L19.517 12.1173L19.5175 12.1168C20.079 11.5552 20.3599 11.2743 20.3476 10.913C20.3353 10.5516 20.0346 10.2509 19.4332 9.64943L13.4791 3.69536C12.8776 3.09391 12.5769 2.79319 12.2155 2.7809C11.8541 2.76862 11.5731 3.04958 11.0112 3.61149");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
