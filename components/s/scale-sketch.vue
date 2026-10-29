<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/a/ar6plbklz.css';
import '../../css/t/tb121gpsz.css';
import '../../css/l/lt7_g7bom.css';
import '../../css/y/yncubmr0l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ar6plbklz wm-k"/><path class="tb121gpsz wm-a"/><path class="lt7_g7bom wm-k"/><path class="wm-a yncubmr0l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:scale-sketch" /></template>
