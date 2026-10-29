<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/s/s5q54hbds.css';
import '../../css/v/vqv71sbfv.css';
import '../../css/d/d4zzgtbcx.css';
import '../../css/m/mwx29-nua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="s5q54hbds wm-k"/><path class="vqv71sbfv wm-a"/><path class="d4zzgtbcx wm-k"/><path class="mwx29-nua wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:underline-sketch" /></template>
