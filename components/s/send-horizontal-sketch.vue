<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/s/sqv44pbla.css';
import '../../css/w/w0d6mrbql.css';
import '../../css/y/yktpx186r.css';
import '../../css/i/iv9vkmb4i.css';
import '../../css/v/vdb1j03ad.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="sqv44pbla"/><path class="w0d6mrbql wm-k"/><path class="wm-a yktpx186r"/><path class="iv9vkmb4i wm-k"/><path class="vdb1j03ad wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:send-horizontal-sketch" /></template>
