<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/b/bdaokmb1w.css';
import '../../css/v/vmpmitpae.css';
import '../../css/d/dj86_u4nv.css';
import '../../css/q/qy2dwvndc.css';
import '../../css/v/vug_rebuj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="bdaokmb1w wm-k"/><path class="vmpmitpae wm-a"/><path class="dj86_u4nv wm-shadow"/><path class="qy2dwvndc wm-k"/><path class="vug_rebuj wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:tv-engrave" /></template>
