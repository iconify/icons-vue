<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="crcnkfctu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:voice-guidance-off" /></template>
<style>
.crcnkfctu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.5 16.473V19.5l-5-4.5h-4V9h1.6m5.299-2.609L12.5 4.5v4.073m2.828.599q.16.16.301.337t.261.369t.217.396t.172.417q.074.214.123.435q.05.221.074.446t.023.451t-.028.451m.85-6.219q.239.201.461.42q.221.22.424.458q.202.237.385.491q.182.253.342.521t.298.548t.252.571t.203.589t.153.605q.065.305.103.615q.039.31.051.622q.013.311 0 .623t-.052.622q-.04.309-.104.615q-.065.305-.155.604t-.204.589t-.253.571M3 3l18 18");
}

</style>
