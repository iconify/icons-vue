<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/e/ejyg5ybet.css';
import '../../css/v/vxoc_pbww.css';
import '../../css/i/ij72ljbex.css';
import '../../css/e/eez02jb3b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ejyg5ybet wm-k"/><path class="vxoc_pbww wm-shadow"/><path class="ij72ljbex wm-k"/><path class="eez02jb3b wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:marigold-engrave" /></template>
