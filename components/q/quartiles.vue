<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="admu8z7_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:quartiles" /></template>
<style>
.admu8z7_b {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.5 18.25q1.796 0 4.351-6.822Q9.539 4.25 12 4.25t5.149 7.178q2.555 6.822 4.351 6.822q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-19q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T1.75 19t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014m14 0h2.496q-1.24-1.476-2.496-4.405zm-1.318-7.74q-1.396-3.429-2.432-4.388V18.25H15V11q0-.135.047-.261q.047-.127.135-.229m-3.932 7.74V6.122q-1.036.959-2.432 4.388q.088.102.135.229Q9 10.865 9 11v7.25zm-3.75 0v-4.405q-1.256 2.929-2.496 4.405z");
}

</style>
