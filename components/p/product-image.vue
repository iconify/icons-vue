<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="doc2e23be"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:product-image" /></template>
<style>
.doc2e23be {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.375 3.25h9.25q2.123 0 3.624 1.501t1.501 3.624v7.25q0 1.738-1.006 3.059L15.03 12.97q-.105-.106-.243-.163t-.287-.057t-.287.057t-.243.163L12 14.939L8.53 11.47q-.105-.106-.243-.163T8 11.25t-.287.057t-.243.163l-5 5q-.076.076-.128.17q-.092-.489-.092-1.015v-7.25q0-2.123 1.501-3.624T7.375 3.25M2.657 17.667q.375.862 1.094 1.582q1.501 1.501 3.624 1.501h9.25q1.738 0 3.059-1.006L14.5 14.561l-1.97 1.969q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094L8 13.061L3.53 17.53q-.105.106-.243.163T3 17.75q-.182 0-.343-.083M16 6.5q-2.5 0-2.5 2.5t2.5 2.5T18.5 9T16 6.5");
}

</style>
