<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/i/iyrqk-7tp.css';
import '../../css/q/q-j_s-bsp.css';
import '../../css/v/vh4_jvb7b.css';
import '../../css/j/jofkexr8t.css';
import '../../css/y/y4nh-g7yf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="iyrqk-7tp wm-k"/><path class="q-j_s-bsp wm-shadow"/><path class="vh4_jvb7b wm-k"/><path class="jofkexr8t wm-k"/><path class="wm-a y4nh-g7yf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:mehndi-hand-engrave" /></template>
