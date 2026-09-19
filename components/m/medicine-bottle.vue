<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/i/ipf2vu9op.css';
import '../../css/f/fzm2rccme.css';
import '../../css/p/p_61p5bej.css';
import '../../css/b/btj-cobvn.css';
import '../../css/t/t6-8_dbpu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="ipf2vu9op"/><path class="fzm2rccme"/><path class="p_61p5bej"/><path class="btj-cobvn"/><path class="t6-8_dbpu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:medicine-bottle" /></template>
