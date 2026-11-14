<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q5wde_bbn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:review-resolve" /></template>
<style>
.q5wde_bbn {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m7.682 19.574l-4.423 1.63q-.125.046-.259.046t-.259-.046q-.07-.026-.133-.064t-.117-.089t-.098-.11t-.074-.127t-.048-.139t-.02-.145q-.003-.074.008-.147q.012-.073.037-.142l1.63-4.423q-2.203-4.015-.264-8.244q2.015-4.394 6.773-5.249t8.176 2.564t2.564 8.176t-5.249 6.773q-4.229 1.939-8.244-.264M11 12.939L9.03 10.97q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014t-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.106.105-.163.243t-.057.287t.057.287t.163.243l2.5 2.5q.105.106.243.163t.287.057t.287-.057t.243-.163l4.5-4.5q.106-.105.163-.243t.057-.287t-.057-.287t-.163-.243q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014t-.146.014q-.073.015-.141.043t-.13.069t-.113.094z");
}

</style>
