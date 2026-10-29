<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/f/f--02_bkw.css';
import '../../css/h/h38dysxin.css';
import '../../css/l/l9kn83bwd.css';
import '../../css/p/psyzc1_dw.css';
import '../../css/i/igb16csex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="f--02_bkw wm-k"/><path class="h38dysxin wm-a"/><path class="l9kn83bwd wm-shadow"/><path class="psyzc1_dw wm-k"/><path class="igb16csex wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:wand-engrave" /></template>
