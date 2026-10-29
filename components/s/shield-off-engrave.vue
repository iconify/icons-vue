<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/t/tep-2nb4r.css';
import '../../css/o/ol-kpp5cg.css';
import '../../css/r/rhuf83w6v.css';
import '../../css/r/ri2e-qbwa.css';
import '../../css/q/qr4ochb5c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="tep-2nb4r wm-k"/><path class="ol-kpp5cg wm-s"/><path class="rhuf83w6v wm-shadow"/><path class="ri2e-qbwa wm-k"/><path class="qr4ochb5c wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:shield-off-engrave" /></template>
