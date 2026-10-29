<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/e/ehzelgb4k.css';
import '../../css/o/ol-kpp5cg.css';
import '../../css/m/msqtke50b.css';
import '../../css/z/zzu7z6b8x.css';
import '../../css/q/qr4ochb5c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ehzelgb4k wm-k"/><path class="ol-kpp5cg wm-s"/><path class="msqtke50b wm-shadow"/><path class="wm-k zzu7z6b8x"/><path class="qr4ochb5c wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:star-off-engrave" /></template>
