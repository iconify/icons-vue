<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nynx0y2mp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:volt" /></template>
<style>
.nynx0y2mp {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.752 4.752Q1.75 7.754 1.75 12t3.002 7.248T12 22.25t7.248-3.002T22.25 12t-3.002-7.248T12 1.75T4.752 4.752m5.122 6.998H15.5q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 .122-.038.237q-.039.116-.112.213l-4.5 6q-.09.119-.218.195t-.276.097t-.292-.015t-.264-.127q-.059-.044-.108-.099q-.05-.055-.087-.119q-.038-.063-.063-.133q-.024-.07-.034-.143t-.007-.147t.022-.145t.051-.138t.076-.126l3.6-4.8H8.5q-.22 0-.406-.119q-.125-.081-.21-.203t-.117-.269q-.032-.145-.005-.292q.026-.147.107-.273l4.5-7q.04-.062.091-.115q.052-.053.112-.095t.129-.072q.067-.029.14-.045q.072-.016.146-.017t.146.012q.073.013.142.04t.131.067q.125.081.21.203t.117.269q.032.145.005.292q-.026.147-.107.273z");
}

</style>
