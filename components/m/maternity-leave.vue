<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ncx48jb2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:maternity-leave" /></template>
<style>
.ncx48jb2p {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11 1.75q-2.75 0-2.75 2.75T11 7.25t2.75-2.75T11 1.75M7.75 21v-5.909q-.759-3.125.267-5.176Q9.099 7.75 11.5 7.75q2.811 0 4.53 1.72q2.001 2 1.198 5.212q-.032.126-.104.234l-.874 1.311V21q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T14.75 21v-5q0-.227.126-.416l.926-1.389q.531-2.301-.832-3.665q-1.281-1.28-3.47-1.28q-1.474 0-2.142 1.335q-.792 1.586-.13 4.233q.022.09.022.182v6q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T7.75 21");
}

</style>
