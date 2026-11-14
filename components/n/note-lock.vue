<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z2a_a6aaw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:note-lock" /></template>
<style>
.z2a_a6aaw {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6 3.25Q3.25 3.25 3.25 6v12q0 2.75 2.75 2.75h10q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T15.25 20v-2.5q0-2.25 2.25-2.25H20q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146V6q0-2.75-2.75-2.75zm4.5 6.5V9.5q0-1 1-1t1 1v.25zm3.5.328q.275.162.518.404q.732.732.732 1.768v1q0 1.036-.732 1.768t-1.768.732h-2.5q-1.036 0-1.768-.732T7.75 13.25v-1q0-1.768 1.25-2.286V9.5Q9 7 11.5 7T14 9.5zm6.53 6.452q-.105.106-.243.163T20 16.75h-2.5q-.75 0-.75.75V20q0 .149-.057.287t-.163.243z");
}

</style>
