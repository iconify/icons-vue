<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/s/sh7b6nbow.css';
import '../../css/g/g1toltbnd.css';
import '../../css/m/m-mvczblc.css';
import '../../css/n/nuurcfg1w.css';
import '../../css/l/lz811wb3l.css';
import '../../css/x/xkns3xb2a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="sh7b6nbow wm-k"/><path class="g1toltbnd wm-a"/><path class="m-mvczblc wm-shadow"/><path class="nuurcfg1w wm-k"/><path class="lz811wb3l wm-a"/><path class="wm-k xkns3xb2a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:pen-tool-engrave" /></template>
