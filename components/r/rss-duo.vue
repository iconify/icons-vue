<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/i/i6g3_sbrr.css';
import '../../css/w/wi2sckbls.css';
import '../../css/w/wgi9_72zv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="i6g3_sbrr"/><path class="wi2sckbls"/><path class="wgi9_72zv wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:rss-duo" /></template>
