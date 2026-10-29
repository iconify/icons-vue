<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/o/olsfd0b0d.css';
import '../../css/r/rkxb5-bsz.css';
import '../../css/j/jh5_0cbif.css';
import '../../css/e/ehz_gxbyn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="olsfd0b0d wm-k"/><path class="rkxb5-bsz wm-shadow"/><path class="jh5_0cbif wm-k"/><path class="ehz_gxbyn wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:speaker-engrave" /></template>
