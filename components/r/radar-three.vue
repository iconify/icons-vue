<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/j/jjtab5g6w.css';
import '../../css/t/tv-vqab4x.css';
import '../../css/g/g4-f7hwxf.css';
import '../../css/t/tqb_6nb6c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="jjtab5g6w"/><path class="tv-vqab4x"/><path class="g4-f7hwxf"/><circle class="tqb_6nb6c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:radar-three" /></template>
