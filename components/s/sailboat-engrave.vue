<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/y/ywn0ijbmf.css';
import '../../css/f/f5-lpey4g.css';
import '../../css/y/ypv0z_bsz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ywn0ijbmf"/><path class="f5-lpey4g wm-shadow"/><path class="ypv0z_bsz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:sailboat-engrave" /></template>
