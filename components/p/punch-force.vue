<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t0a2mokwe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:punch-force" /></template>
<style>
.t0a2mokwe {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.752 9.252Q1.75 12.254 1.75 16.5q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h19q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146q0-4.246-3.002-7.248T12 6.25T4.752 9.252m12.629 3.345l-5.75 3.25q-.064.036-.12.085q-.056.048-.102.106t-.079.124t-.053.137t-.025.145t.004.147t.032.144t.059.134t.085.12q.048.056.106.102t.124.079t.137.053t.145.025t.147-.004t.144-.032t.134-.059l5.75-3.25q.064-.036.12-.085q.056-.048.102-.106t.079-.124t.053-.137t.025-.145t-.004-.147t-.032-.144t-.059-.134t-.085-.12t-.106-.102t-.124-.079t-.137-.053t-.145-.025t-.147.004t-.144.032q-.07.023-.134.059");
}

</style>
