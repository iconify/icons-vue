<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/h/hduqftrhx.css';
import '../../css/v/viydr2vqu.css';
import '../../css/l/lxc7q5bue.css';
import '../../css/o/opucl5yls.css';
import '../../css/i/i770uqt7u.css';
import '../../css/l/lbsx3ub7i.css';
import '../../css/f/fvbk-8bio.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="hduqftrhx wm-k"/><path class="viydr2vqu wm-s"/><path class="lxc7q5bue wm-shadow"/><path class="opucl5yls wm-k"/><path class="i770uqt7u wm-a"/><path class="lbsx3ub7i wm-k"/><path class="fvbk-8bio wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:paper-fan-engrave" /></template>
