<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/x/x4_9b04xw.css';
import '../../css/b/buzsznbhz.css';
import '../../css/y/y2dwv2bgr.css';
import '../../css/a/arddq2bwc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="x4_9b04xw"/><path class="buzsznbhz wm-a"/><path class="wm-k y2dwv2bgr"/><path class="arddq2bwc wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:replace-sketch" /></template>
