<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/m/m1e1revmv.css';
import '../../css/q/qzn_ctbxq.css';
import '../../css/j/jac47ganm.css';
import '../../css/q/qiqn0dn5q.css';
import '../../css/m/mq-ynobqs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="m1e1revmv"/><path class="qzn_ctbxq wm-k"/><path class="jac47ganm wm-a"/><path class="qiqn0dn5q wm-k"/><path class="mq-ynobqs wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:wallet-cards-sketch" /></template>
