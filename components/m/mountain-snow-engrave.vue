<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/t/te6upj5cp.css';
import '../../css/t/ts_wh6bwk.css';
import '../../css/l/lu45pfb1y.css';
import '../../css/z/z2v1f6pmt.css';
import '../../css/k/kc1_78x9b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="te6upj5cp wm-k"/><path class="ts_wh6bwk wm-a"/><path class="lu45pfb1y wm-shadow"/><path class="wm-k z2v1f6pmt"/><path class="kc1_78x9b wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:mountain-snow-engrave" /></template>
