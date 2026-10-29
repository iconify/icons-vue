<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/d/d69hxya3k.css';
import '../../css/c/cxngk4btb.css';
import '../../css/x/xj8d2h4lb.css';
import '../../css/u/udv511-gg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="d69hxya3k"/><path class="cxngk4btb wm-k"/><path class="wm-k xj8d2h4lb"/><path class="udv511-gg wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:thumbs-down-sketch" /></template>
