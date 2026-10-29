<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/k/ka0cffbnj.css';
import '../../css/t/tke3h262y.css';
import '../../css/h/hpu_rfbxt.css';
import '../../css/g/gfg0fpbjr.css';
import '../../css/o/obbqqccjp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ka0cffbnj"/><path class="tke3h262y wm-k"/><path class="hpu_rfbxt wm-a"/><path class="gfg0fpbjr wm-k"/><path class="obbqqccjp wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:shield-alert-sketch" /></template>
