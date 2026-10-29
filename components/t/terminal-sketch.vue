<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/o/o4qq2hmsv.css';
import '../../css/r/re7id0y1c.css';
import '../../css/s/sx20ad8rv.css';
import '../../css/u/unn-0zbjb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="o4qq2hmsv"/><path class="re7id0y1c wm-a"/><path class="sx20ad8rv wm-k"/><path class="unn-0zbjb wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:terminal-sketch" /></template>
