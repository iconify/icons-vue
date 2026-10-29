<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/i/ik1oxmbfh.css';
import '../../css/k/ku5p8_kxi.css';
import '../../css/h/h7xnus5-e.css';
import '../../css/u/unefcsbmw.css';
import '../../css/a/anua2ob4h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ik1oxmbfh wm-k"/><path class="ku5p8_kxi wm-shadow"/><path class="h7xnus5-e wm-k"/><path class="unefcsbmw wm-k"/><path class="anua2ob4h wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:watch-engrave" /></template>
