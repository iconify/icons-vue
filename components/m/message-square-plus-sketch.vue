<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/q/q082x0big.css';
import '../../css/s/sdcxhgb1a.css';
import '../../css/y/y4hr1otxh.css';
import '../../css/n/nxd81s02k.css';
import '../../css/s/shk5hnb7d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="q082x0big"/><path class="sdcxhgb1a wm-k"/><path class="wm-a y4hr1otxh"/><path class="nxd81s02k wm-k"/><path class="shk5hnb7d wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:message-square-plus-sketch" /></template>
