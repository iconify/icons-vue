<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/q/qyfmmpgqr.css';
import '../../css/x/x96k-accp.css';
import '../../css/q/q-ykn3bot.css';
import '../../css/z/z-a4k4b8u.css';
import '../../css/w/wneoubc6n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="qyfmmpgqr wm-k"/><path class="wm-a x96k-accp"/><path class="q-ykn3bot wm-shadow"/><path class="wm-k z-a4k4b8u"/><path class="wm-a wneoubc6n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:sprout-engrave" /></template>
