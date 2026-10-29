<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/w/wmiiyybyy.css';
import '../../css/i/ikidij4md.css';
import '../../css/f/fqyx1zd_r.css';
import '../../css/p/psqpflbbk.css';
import '../../css/w/wbezozb6y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="wmiiyybyy"/><path class="ikidij4md wm-k"/><path class="fqyx1zd_r wm-a"/><path class="psqpflbbk wm-k"/><path class="wbezozb6y wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:pencil-sketch" /></template>
