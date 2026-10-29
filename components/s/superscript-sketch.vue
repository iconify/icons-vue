<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/n/n9ycfgbml.css';
import '../../css/d/drb1r_bnp.css';
import '../../css/k/ktmbf04te.css';
import '../../css/t/t1kem48fi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="n9ycfgbml wm-k"/><path class="drb1r_bnp wm-a"/><path class="ktmbf04te wm-k"/><path class="t1kem48fi wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:superscript-sketch" /></template>
