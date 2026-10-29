<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/l/l85ttcc8d.css';
import '../../css/n/nj_k7fbow.css';
import '../../css/f/fyutsyjov.css';
import '../../css/i/iy5v8lbll.css';
import '../../css/t/tmj-ls_rw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="l85ttcc8d wm-k"/><path class="nj_k7fbow wm-a"/><path class="fyutsyjov wm-shadow"/><path class="iy5v8lbll wm-k"/><path class="tmj-ls_rw wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:swords-engrave" /></template>
