<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/v/v6mjv2pfr.css';
import '../../css/k/kbr7fzbsv.css';
import '../../css/k/kebgbt-gk.css';
import '../../css/x/xu_bh3b0d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="v6mjv2pfr wm-k"/><path class="kbr7fzbsv wm-k"/><path class="kebgbt-gk wm-k"/><path class="wm-a xu_bh3b0d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:users-sketch" /></template>
