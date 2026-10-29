<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/y/y51z3iz3m.css';
import '../../css/i/ioq3g7b0x.css';
import '../../css/o/oqx77ybwi.css';
import '../../css/y/yd5k-hbzc.css';
import '../../css/h/hm1lzmgnv.css';
import '../../css/v/v2jkl0frg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="wm-k y51z3iz3m"/><path class="ioq3g7b0x wm-shadow"/><path class="oqx77ybwi wm-k"/><path class="wm-a yd5k-hbzc"/><path class="hm1lzmgnv wm-s"/><path class="v2jkl0frg wm-k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:oven-engrave" /></template>
