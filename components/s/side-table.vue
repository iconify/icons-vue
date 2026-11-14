<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y5fu38-xp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:side-table" /></template>
<style>
.y5fu38-xp {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.25 7.001v-.002q0-1.605 3.184-2.49q2.735-.76 6.566-.76t6.566.76q3.186.885 3.184 2.49q.002 1.607-3.184 2.492q-2.463.684-5.816.752v9.507h3.75q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-9q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014h3.75v-9.507q-3.353-.068-5.816-.752q-3.184-.885-3.184-2.49");
}

</style>
