<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/y/yz047xxvk.css';
import '../../css/l/lq_kbcb4p.css';
import '../../css/a/a__jogb4x.css';
import '../../css/v/v_rv7fwiy.css';
import '../../css/h/h1d8v6btm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="yz047xxvk"/><path class="lq_kbcb4p wm-k"/><path class="a__jogb4x wm-a"/><path class="v_rv7fwiy wm-k"/><path class="h1d8v6btm wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:receipt-sketch" /></template>
