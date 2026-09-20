<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/k/kebp8vbig.css';
import '../../css/u/ui8u4ns2y.css';
import '../../css/a/axz1i1r4g.css';
import '../../css/d/dlgm9h3nj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="kebp8vbig"/><path class="ui8u4ns2y"/><path class="axz1i1r4g"/><path class="dlgm9h3nj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:palette-round-linear" /></template>
