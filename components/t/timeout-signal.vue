<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jr1crab1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:timeout-signal" /></template>
<style>
.jr1crab1k {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.75 3.25h14.5q3 0 3 3t-3 3H15v10q0 3-3 3t-3-3v-10H5.25v.25q0 1.25 1.25 1.25H7q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043T7 12.25h-.5q-2.75 0-2.75-2.75v-.351q-2-.45-2-2.899q0-3 3-3m5.75 6v10q0 1.5 1.5 1.5t1.5-1.5v-10z");
}

</style>
