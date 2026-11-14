<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p1oey2btc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:medicine-search" /></template>
<style>
.p1oey2btc {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.166 4.166Q1.75 6.583 1.75 10t2.416 5.834T10 18.25q3.036 0 5.282-1.907l5.188 5.187q.052.053.113.094t.13.069t.141.043t.146.014q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113l-5.187-5.188Q18.25 13.036 18.25 10q0-3.417-2.416-5.834T10 1.75T4.166 4.166m9.192 6.364l-1.414 1.414l-1.414 1.414q-1.944 1.944-3.888 0t0-3.888l1.414-1.414L9.47 6.642q1.944-1.944 3.888 0t0 3.888");
}

</style>
