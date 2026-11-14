<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ojjfo6rdy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:simulator" /></template>
<style>
.ojjfo6rdy {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6 2.75h9q1.76 0 3.005 1.245T19.25 7v.013Q19.065 7 18.875 7h-.75q-1.916 0-3.27 1.355t-1.355 3.27v4.625h-3.25v2.5H13q.139 0 .268.049q.129.05.232.142q.007.517.113.992q-.052.073-.12.132t-.148.101t-.168.063t-.177.021H6q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043T6 18.75h2.75v-2.5H6q-1.76 0-3.005-1.245T1.75 12V7q0-1.76 1.245-3.005T6 2.75m12.125 5.5h.75q3.375 0 3.375 3.375v7.25q0 3.375-3.375 3.375h-.75q-3.375 0-3.375-3.375v-7.25q0-3.375 3.375-3.375m0 1.5q-1.875 0-1.875 1.875v7.25q0 1.875 1.875 1.875h.75q1.875 0 1.875-1.875v-7.25q0-1.875-1.875-1.875zm.75 1.25q.23 0 .375.084V12q0 1.76-1.245 3.005q-.243.243-.505.438v-3.818q0-.625.625-.625z");
}

</style>
