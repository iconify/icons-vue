<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/p/po3mwhbob.css';
import '../../css/c/csggutbvi.css';
import '../../css/c/cpa-a-bgn.css';
import '../../css/z/z_t_5xs2k.css';
import '../../css/k/kwkygzbyd.css';
import '../../css/u/umhjfobpc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="po3mwhbob"/><path class="csggutbvi wm-a"/><path class="cpa-a-bgn wm-s"/><path class="wm-k z_t_5xs2k"/><path class="kwkygzbyd wm-a"/><path class="umhjfobpc wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:plug-zap-sketch" /></template>
