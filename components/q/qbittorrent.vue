<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m1by-e7kb.css';
import '../../css/w/we4b9qbwr.css';
import '../../css/v/vi6f9fbrx.css';
import '../../css/q/qf8rzgboj.css';
import '../../css/a/aj3wjqbjk.css';
import '../../css/z/zmwvj3_5w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVGhslODemx" x1="-545.332" x2="-545.12" y1="1053.675" y2="1053.291" gradientTransform="matrix(992 0 0 -992 541102 1045278)" gradientUnits="userSpaceOnUse"><stop offset="0" class="m1by-e7kb"/><stop offset="1" class="we4b9qbwr"/></linearGradient><circle fill="url(#SVGhslODemx)" class="vi6f9fbrx"/><path class="qf8rzgboj"/><path class="aj3wjqbjk"/><path class="zmwvj3_5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:qbittorrent" /></template>
