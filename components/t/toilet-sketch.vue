<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/m/mdoim3brn.css';
import '../../css/j/jrf-bccmn.css';
import '../../css/b/bpaqc2ohf.css';
import '../../css/t/t23h3n3fw.css';
import '../../css/w/ww__7yboz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="mdoim3brn"/><path class="jrf-bccmn wm-k"/><path class="bpaqc2ohf wm-a"/><path class="t23h3n3fw wm-k"/><path class="wm-a ww__7yboz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:toilet-sketch" /></template>
