<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tbyo-__hk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:washer-dryer" /></template>
<style>
.tbyo-__hk {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M15 1.25H9q-1.76 0-3.005 1.245T4.75 5.5v13q0 1.76 1.245 3.005T9 22.75h6q1.76 0 3.005-1.245T19.25 18.5v-13q0-1.76-1.245-3.005T15 1.25M19.25 12q0 .074-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-13q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T4.75 12t.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014h13q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146M15 7q0 3-3 3T9 7t3-3t3 3m-3 7q3 0 3 3t-3 3t-3-3t3-3");
}

</style>
