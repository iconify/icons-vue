<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="chpbl9egd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:video-check" /></template>
<style>
.chpbl9egd {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.875 5.25h4.25q2.123 0 3.624 1.501q1.09 1.091 1.389 2.509l2.352-1.373q1.25-.729 2.505-.008t1.255 2.168v3.906q0 1.447-1.255 2.168t-2.505-.008l-2.352-1.373q-.299 1.418-1.389 2.509q-1.501 1.501-3.624 1.501h-4.25q-2.123 0-3.624-1.501T1.75 13.625v-3.25q0-2.123 1.501-3.624T6.875 5.25m1.355 7.419l-1.2-1.199q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014t-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.106.105-.163.243T5.75 12t.057.287t.163.243l1.75 1.75q.105.106.243.163t.287.057t.287-.057t.243-.163l.02-.02l3.25-3.5q.05-.054.089-.117t.064-.132t.037-.142t.009-.147t-.019-.145t-.048-.139t-.074-.127q-.044-.06-.098-.111q-.054-.05-.117-.089t-.132-.064t-.142-.038q-.073-.011-.147-.008t-.145.019t-.139.048t-.127.074q-.06.044-.111.098z");
}

</style>
