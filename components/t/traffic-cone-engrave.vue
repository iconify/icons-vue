<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/v/vgrfljsfn.css';
import '../../css/z/zxbcp0r1n.css';
import '../../css/z/zo3y1ub3k.css';
import '../../css/d/d0rm88b6m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="vgrfljsfn wm-k"/><path class="wm-shadow zxbcp0r1n"/><path class="wm-k zo3y1ub3k"/><path class="d0rm88b6m wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:traffic-cone-engrave" /></template>
