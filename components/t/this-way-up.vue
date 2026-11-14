<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u3v1r7b0x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:this-way-up" /></template>
<style>
.u3v1r7b0x {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.5 3.75h7q1.76 0 3.005 1.245T19.75 8v8q0 1.76-1.245 3.005T15.5 20.25h-7q-1.76 0-3.005-1.245T4.25 16V8q0-1.76 1.245-3.005T8.5 3.75m2.969 3.72l-2.999 3q-.106.105-.163.243T8.25 11t.057.287t.163.243q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094l1.72-1.719V16q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146V9.811l1.72 1.719q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113l-2.999-3h-.001q-.105-.106-.243-.163T12 7.25t-.287.057t-.243.163z");
}

</style>
