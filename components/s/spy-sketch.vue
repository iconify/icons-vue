<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/e/eab5obbwx.css';
import '../../css/s/s0a204b1r.css';
import '../../css/y/ysas-lb9p.css';
import '../../css/l/le_23rbrp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="eab5obbwx"/><path class="s0a204b1r wm-k"/><path class="wm-k ysas-lb9p"/><path class="le_23rbrp wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:spy-sketch" /></template>
