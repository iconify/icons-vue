<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/e/ez05224-i.css';
import '../../css/w/wciayxbdl.css';
import '../../css/l/llxyupbek.css';
import '../../css/f/fnr8gob4l.css';
import '../../css/n/nsiaxmbcn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ez05224-i"/><path class="wciayxbdl wm-k"/><path class="llxyupbek wm-a"/><path class="fnr8gob4l wm-k"/><path class="nsiaxmbcn wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:message-square-code-sketch" /></template>
