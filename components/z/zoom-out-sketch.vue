<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/w/wnzp-ncyf.css';
import '../../css/x/x7annnbrx.css';
import '../../css/q/qktlr5byx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="wnzp-ncyf"/><path class="wm-k x7annnbrx"/><path class="qktlr5byx wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:zoom-out-sketch" /></template>
