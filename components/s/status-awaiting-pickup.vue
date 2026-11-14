<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="olt2mbcoi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:status-awaiting-pickup" /></template>
<style>
.olt2mbcoi {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M15 3.25q3.796 0 3.99 2.477l-1.801 2.025q-.091.103-.14.231Q17 8.112 17 8.25v6.25q0 .074.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014h4q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146V8.25q0-.138-.049-.267q-.049-.128-.14-.231l-1.818-2.045Q20.307 1.75 15 1.75q-6.481 0-6.961 4.5H4.25q-1.036 0-1.768.732T1.75 8.75q0 1.581 1 2.162V20q0 2.25 2.25 2.25h7.25q2.25 0 2.25-2.25v-9.088q1-.581 1-2.162q0-2.5-2.5-2.5H9.561q.52-3 5.439-3m-5.5 17.5v-9.5H13V20q0 .75-.75.75zM8 11.25v9.5H5q-.75 0-.75-.75v-8.75zm11.75-4.121L21 8.535v5.215h-2.5V8.535z");
}

</style>
