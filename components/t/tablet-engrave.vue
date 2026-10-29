<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/e/enf_cwn5v.css';
import '../../css/i/i_obi8n6h.css';
import '../../css/c/cf9266bin.css';
import '../../css/o/oztr_bbxl.css';
import '../../css/c/c4bit6l7l.css';
import '../../css/m/mvmtu_3lg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="enf_cwn5v wm-k"/><path class="i_obi8n6h wm-a"/><path class="cf9266bin wm-shadow"/><path class="oztr_bbxl wm-k"/><path class="c4bit6l7l wm-k"/><path class="mvmtu_3lg wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:tablet-engrave" /></template>
