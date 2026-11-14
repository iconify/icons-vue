<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dqxmc1m7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:not-interested" /></template>
<style>
.dqxmc1m7p {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19.815 16.986L7.013 4.185Q9.209 2.747 12 2.747q3.832 0 6.542 2.71T21.25 12q.001 2.79-1.435 4.986M4.03 2.97l17 17q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094l-17-17q-.053-.052-.094-.113t-.069-.13t-.043-.141T2.75 3.5t.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043q.072-.014.146-.014t.146.014q.073.015.141.043t.13.069t.113.094M12 21.253q2.791 0 4.987-1.438L4.185 7.014Q2.749 9.209 2.75 12q-.001 3.832 2.708 6.543q2.71 2.71 6.542 2.71");
}

</style>
