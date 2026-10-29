<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/b/bkqxbnb8b.css';
import '../../css/u/usypnx0pj.css';
import '../../css/d/db_fcac8o.css';
import '../../css/j/jp-rqubck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="bkqxbnb8b wm-k"/><path class="usypnx0pj wm-s"/><path class="db_fcac8o wm-k"/><path class="jp-rqubck wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:shield-off-sketch" /></template>
