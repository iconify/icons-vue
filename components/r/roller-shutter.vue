<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="js72wtnja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:roller-shutter" /></template>
<style>
.js72wtnja {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19.5 1.75h-15q-.932 0-1.591.659T2.25 4q0 2.121 2 2.243V21q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h14q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146V6.243q2-.122 2-2.243q0-2.25-2.25-2.25M18.25 15H5.75v-3.75h12.5zm-12.5 1.5h12.5v3.75H5.75zm0-6.75v-3.5h12.5v3.5z");
}

</style>
