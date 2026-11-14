<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v82u5j3-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:pin-wildfire" /></template>
<style>
.v82u5j3-m {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.282 20.093Q8.439 22.25 12 22.25t5.718-2.157Q19.75 18.061 19.75 15q0-4.639-2.936-7.994q-.154-.177-.382-.234q-.072-.018-.146-.021q-.073-.004-.146.007t-.143.036t-.133.063t-.118.088t-.099.109t-.075.126t-.05.138q-.155.621-.457 1.191q-.765-3.916-4.693-6.16q-.111-.064-.238-.087q-.147-.027-.292.005q-.146.031-.269.116t-.203.211t-.108.272q-.457 2.513-2.657 5.93Q4.25 12.456 4.25 15q0 3.061 2.032 5.093M12 19.25q-3.25 0-3.25-3.25q0-1.292 1.617-3.151q.71-.816 1.009-1.265q.041-.061.093-.114q.052-.052.114-.093q.061-.041.129-.07q.068-.028.141-.042t.146-.015q.074 0 .147.014q.072.015.14.043t.13.069q.125.083.208.208q.299.449 1.009 1.265Q15.25 14.708 15.25 16q0 3.25-3.25 3.25");
}

</style>
