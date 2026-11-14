<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zuqe_h21c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:pin-search" /></template>
<style>
.zuqe_h21c {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.75 8.5q0 5.832 5.745 11.055q.052.047.111.083t.124.062t.132.037q.069.013.138.013t.138-.013q.068-.012.132-.037q.065-.025.124-.062q.059-.036.111-.083Q15.25 14.332 15.25 8.5q0-2.589-1.831-4.419Q11.589 2.25 9 2.25T4.581 4.081Q2.75 5.911 2.75 8.5m3.5 0q0-2.75 2.75-2.75t2.75 2.75T9 11.25T6.25 8.5m11 5.75q-3 0-3 3t3 3q.97 0 1.626-.313l1.344 1.343q.052.053.113.094t.13.069t.141.043t.146.014q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113l-1.343-1.344q.313-.656.313-1.626q0-3-3-3");
}

</style>
