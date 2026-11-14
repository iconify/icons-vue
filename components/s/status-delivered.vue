<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ks3we1b1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:status-delivered" /></template>
<style>
.ks3we1b1z {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.935 9.143Q2.75 10.154 2.75 11.711v6.164q0 3.375 3.375 3.375h11.75q3.375 0 3.375-3.375v-6.164q0-1.557-1.185-2.568L14.19 4.132q-2.19-1.866-4.38 0zm6.815 7.046l4.72-4.719q.052-.053.113-.094t.13-.069t.141-.043t.146-.014t.146.014q.073.015.141.043t.13.069q.061.041.113.094q.106.105.163.243t.057.287t-.057.287t-.163.243l-5.25 5.25q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094l-2.75-2.75q-.106-.105-.163-.243T7.25 14.5t.057-.287t.163-.243q.052-.053.113-.094t.13-.069t.141-.043T8 13.75t.146.014q.073.015.141.043t.13.069t.113.094z");
}

</style>
