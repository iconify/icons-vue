<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ozg-etkdd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:now-showing" /></template>
<style>
.ozg-etkdd {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19.5 4.75h-15Q2.25 4.75 2.25 7v3q0 .074.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014q1.25 0 1.25 1.25T3 13.25q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141q-.014.072-.014.146v3q0 2.25 2.25 2.25h15q2.25 0 2.25-2.25v-3q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T21 13.25q-1.25 0-1.25-1.25T21 10.75q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146V7q0-2.25-2.25-2.25m-7.366 4.418l1.523.888q1.117.651 1.117 1.944t-1.117 1.944l-1.523.888q-1.125.656-2.255.007q-1.129-.648-1.129-1.951v-1.776q0-1.303 1.129-1.951t2.255.007");
}

</style>
