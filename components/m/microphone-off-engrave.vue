<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/m/miuskzbwk.css';
import '../../css/r/rpq_awb5u.css';
import '../../css/o/ol-kpp5cg.css';
import '../../css/f/fh7k3v94b.css';
import '../../css/g/gfjheqbit.css';
import '../../css/w/wsynvg5ce.css';
import '../../css/q/qr4ochb5c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="miuskzbwk wm-k"/><path class="rpq_awb5u wm-a"/><path class="ol-kpp5cg wm-s"/><path class="fh7k3v94b wm-shadow"/><path class="gfjheqbit wm-k"/><path class="wm-a wsynvg5ce"/><path class="qr4ochb5c wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:microphone-off-engrave" /></template>
