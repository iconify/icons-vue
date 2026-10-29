<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/d/d6p02yb1m.css';
import '../../css/g/g_gpx3b3t.css';
import '../../css/q/qmfyozb_l.css';
import '../../css/h/hwhzvl0qe.css';
import '../../css/d/dnj10ls6m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="d6p02yb1m"/><path class="g_gpx3b3t wm-k"/><path class="qmfyozb_l wm-a"/><path class="hwhzvl0qe wm-k"/><path class="dnj10ls6m wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:message-square-warning-sketch" /></template>
