<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xyayndb2t.css';
import '../../css/w/wxcgd_r6i.css';
import '../../css/k/kdz4acc8r.css';
import '../../css/u/usozxnbrm.css';
import '../../css/m/m_72sd0-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<circle class="xyayndb2t"/><path class="wxcgd_r6i"/><g class="kdz4acc8r"><circle class="usozxnbrm"/><path class="m_72sd0-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:regional-indicator-c" /></template>
