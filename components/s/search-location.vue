<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v6t7nnbif"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:search-location" /></template>
<style>
.v6t7nnbif {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.75 10.5q0-3.21 2.27-5.48t5.48-2.27t5.48 2.27t2.27 5.48q0 2.829-1.762 4.927l4.542 4.543q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094l-4.543-4.542Q13.329 18.25 10.5 18.25q-3.21 0-5.48-2.27T2.75 10.5m1.5 0q0 2.589 1.831 4.419q1.83 1.831 4.419 1.831t4.419-1.831T16.75 10.5t-1.831-4.419Q13.089 4.25 10.5 4.25T6.081 6.081Q4.25 7.911 4.25 10.5m5.775 4.08Q7 12.105 7 9.75q0-3.5 3.5-3.5t3.5 3.5q0 2.355-3.025 4.83q-.05.041-.106.073t-.117.053t-.124.033q-.064.011-.128.011t-.128-.011t-.124-.033t-.117-.053t-.106-.073");
}

</style>
