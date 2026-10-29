<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/e/e1j58ib4f.css';
import '../../css/j/jqsrvlbqh.css';
import '../../css/w/wgr5uv0-u.css';
import '../../css/y/y5dvwo25s.css';
import '../../css/x/x0w6nibqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="e1j58ib4f wm-k"/><path class="jqsrvlbqh wm-s"/><path class="wgr5uv0-u wm-shadow"/><path class="wm-k y5dvwo25s"/><path class="wm-s x0w6nibqk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:message-square-dot-engrave" /></template>
