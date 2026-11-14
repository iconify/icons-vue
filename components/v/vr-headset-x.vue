<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gzeotqocr"/><path class="bs91rl_zw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:vr-headset-x" /></template>
<style>
.bs91rl_zw {
  d: path("M6 5.5c0-3.75 12-3.75 12 0m-2.5 10l5 5m0-5l-5 5");
}

.gzeotqocr {
  d: path("M13.735 13.367q-.182-.149-.387-.264t-.427-.194t-.454-.119t-.467-.04q-.135 0-.27.013q-.134.013-.266.04q-.133.026-.262.065q-.13.04-.254.091q-.125.052-.244.116q-.119.063-.232.138q-.112.076-.217.161q-.104.086-.2.181q-.095.096-.181.2t-.161.217t-.138.232q-.064.119-.116.244q-.051.124-.091.254q-.039.129-.065.262q-.027.132-.04.266q-.013.135-.013.27H5.5q-.147 0-.294-.014t-.291-.044q-.145-.028-.286-.071t-.277-.099t-.266-.126t-.253-.152q-.122-.081-.236-.175t-.218-.198t-.198-.218t-.175-.236t-.152-.253t-.126-.266t-.099-.277t-.071-.286t-.044-.291Q2.5 12.647 2.5 12.5v-4q0-.147.014-.294t.044-.291q.028-.145.071-.286t.099-.277t.126-.266t.152-.253t.175-.236t.198-.218t.218-.198q.114-.094.236-.175q.123-.082.253-.152t.266-.126t.277-.099t.286-.071q.144-.029.291-.044T5.5 5.5h13q.147 0 .294.014t.291.044q.145.028.286.071t.277.099q.136.057.266.126q.13.07.253.152q.122.081.236.175t.218.198t.198.218t.175.236q.082.123.152.253t.126.266t.099.277t.071.286t.044.291t.014.294v4q0 .193-.025.385");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
