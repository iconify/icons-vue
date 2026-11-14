<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="amyc5mw6u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:smart-switch-off" /></template>
<style>
.amyc5mw6u {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18.75 6.875v9.047l-4.5-4.5V8.125q0-3.375-3.375-3.375h-.75q-1.273 0-2.066.48L5.096 2.268q1.032-.518 2.279-.518h6.25q2.123 0 3.624 1.501t1.501 3.624M4.03 2.97l17 17q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094l-17-17q-.053-.052-.094-.113t-.069-.13t-.043-.141T2.75 3.5t.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043q.072-.014.146-.014t.146.014q.073.015.141.043t.13.069t.113.094m13.304 17.192l-4.723-4.722q-.713.31-1.736.31h-.75q-3.375 0-3.375-3.375V9.578l-4.27-4.27q-.23.736-.23 1.567v9.75q0 2.123 1.501 3.624t3.624 1.501h6.25q2.123 0 3.624-1.501z");
}

</style>
