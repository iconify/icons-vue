<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/g/gcb_nac6q.css';
import '../../css/q/qrp9jfhtm.css';
import '../../css/n/ni_p2fxgs.css';
import '../../css/n/nn7f_zb2c.css';
import '../../css/o/ovp7dlb_x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="gcb_nac6q wm-k"/><path class="qrp9jfhtm wm-a"/><path class="ni_p2fxgs wm-shadow"/><path class="nn7f_zb2c wm-k"/><path class="ovp7dlb_x wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:tree-deciduous-engrave" /></template>
