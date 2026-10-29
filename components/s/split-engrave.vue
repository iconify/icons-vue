<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/q/qvk5q1f0x.css';
import '../../css/x/xlmfdgbol.css';
import '../../css/y/yyeasgwwc.css';
import '../../css/h/h65e0tmly.css';
import '../../css/s/s53tgbb5w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="qvk5q1f0x wm-k"/><path class="wm-a xlmfdgbol"/><path class="wm-shadow yyeasgwwc"/><path class="h65e0tmly wm-k"/><path class="s53tgbb5w wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:split-engrave" /></template>
