<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/g/gfuk4nbmr.css';
import '../../css/e/eez02jb3b.css';
import '../../css/i/ij72ljbex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="gfuk4nbmr"/><path class="eez02jb3b wm-a"/><path class="ij72ljbex"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:marigold-duo" /></template>
