<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/j/jmbz2vb9o.css';
import '../../css/z/zlsqrnbma.css';
import '../../css/h/hurexej9d.css';
import '../../css/t/t-at26brw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="jmbz2vb9o"/><path class="wm-k zlsqrnbma"/><path class="hurexej9d wm-k"/><path class="t-at26brw wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:map-sketch" /></template>
