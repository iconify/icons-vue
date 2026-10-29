<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/d/d016bhb4h.css';
import '../../css/b/buaumacrm.css';
import '../../css/f/f4ykpybma.css';
import '../../css/b/bd2t1bccx.css';
import '../../css/f/fqpodu9zv.css';
import '../../css/u/ugnb4kbse.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="d016bhb4h wm-k"/><path class="buaumacrm wm-a"/><path class="f4ykpybma wm-shadow"/><path class="bd2t1bccx wm-k"/><path class="fqpodu9zv wm-a"/><path class="ugnb4kbse wm-k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:paint-roller-engrave" /></template>
