<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/n/nfg8wbbsm.css';
import '../../css/x/x-eug4d4m.css';
import '../../css/u/ubemx3b4f.css';
import '../../css/q/qbdq7ybsf.css';
import '../../css/e/e2h_bnbsu.css';
import '../../css/m/m44p9ib7c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="nfg8wbbsm"/><path class="wm-k x-eug4d4m"/><path class="ubemx3b4f wm-s"/><path class="qbdq7ybsf wm-k"/><path class="e2h_bnbsu wm-a"/><path class="m44p9ib7c wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:server-off-sketch" /></template>
