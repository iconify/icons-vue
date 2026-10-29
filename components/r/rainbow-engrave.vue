<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/s/sr8-7ybpu.css';
import '../../css/a/a88t_lbux.css';
import '../../css/r/r5b1awbki.css';
import '../../css/y/ydpucsi6v.css';
import '../../css/k/kgm9zh0zc.css';
import '../../css/w/wk7jmzmpf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="sr8-7ybpu wm-k"/><path class="a88t_lbux wm-a"/><path class="r5b1awbki wm-shadow"/><path class="wm-k ydpucsi6v"/><path class="kgm9zh0zc wm-k"/><path class="wk7jmzmpf wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:rainbow-engrave" /></template>
