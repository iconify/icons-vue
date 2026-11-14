<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mngosibcd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:parquet-floor" /></template>
<style>
.mngosibcd {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.47 8.719q-.106.105-.163.243t-.057.287v10q0 .149.057.287t.163.243q.027.028.057.052q.101.082.222.125Q2.871 20 3 20q.149 0 .287-.057t.243-.163l3.97-3.969l3.97 3.969l.003.004q.105.104.242.16T12 20t.287-.057t.243-.163l3.97-3.969l3.97 3.969q.105.106.243.163T21 20t.287-.057t.243-.163q.106-.105.163-.243t.057-.287v-10q0-.149-.057-.287t-.163-.243l-4.5-4.5q-.105-.106-.243-.163T16.5 4l-.039.001q-.139.007-.266.064q-.127.056-.225.155h-.001L12 8.189L8.031 4.22H8.03q-.105-.106-.243-.163T7.5 4t-.287.057t-.243.163zm1.28.842l3-3v2.878l-3 3zm4.5-3l3 3v2.878l-3-3zm4.5 3l3-3v2.878l-3 3zm4.5-3l3 3v2.878l-3-3zm3 8v2.878l-3-3v-2.878zm-4.5-.122l-3 3v-2.878l3-3zm-4.5 3l-3-3v-2.878l3 3zm-4.5-3l-3 3v-2.878l3-3z");
}

</style>
