<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/s/s_o715b1n.css';
import '../../css/h/h5g9mcc-j.css';
import '../../css/f/f1z5e3bhu.css';
import '../../css/j/jm7u_x6kk.css';
import '../../css/y/y875pzbpu.css';
import '../../css/e/eshsd_oei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="s_o715b1n wm-k"/><path class="h5g9mcc-j wm-shadow"/><path class="f1z5e3bhu wm-k"/><path class="jm7u_x6kk wm-k"/><path class="wm-a y875pzbpu"/><path class="eshsd_oei wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:witch-hat-engrave" /></template>
