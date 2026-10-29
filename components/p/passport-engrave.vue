<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/t/t2vdistiz.css';
import '../../css/k/k3qcgxbnp.css';
import '../../css/b/buxga7syi.css';
import '../../css/z/zm38tmb2p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="t2vdistiz wm-k"/><path class="k3qcgxbnp wm-shadow"/><path class="buxga7syi wm-k"/><path class="wm-a zm38tmb2p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:passport-engrave" /></template>
