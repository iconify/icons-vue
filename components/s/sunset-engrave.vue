<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/k/k4qkxi46l.css';
import '../../css/i/i8n8d4bmd.css';
import '../../css/l/lyqxg0dtp.css';
import '../../css/d/d7jwdev0a.css';
import '../../css/s/sxdzfouvy.css';
import '../../css/z/z43mx6bwb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="k4qkxi46l wm-k"/><path class="i8n8d4bmd wm-s"/><path class="lyqxg0dtp wm-shadow"/><path class="d7jwdev0a wm-k"/><path class="sxdzfouvy wm-a"/><path class="wm-s z43mx6bwb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:sunset-engrave" /></template>
