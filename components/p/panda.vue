<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/d/dt6m_drdp.css';
import '../../css/q/qy0j17i9e.css';
import '../../css/v/vf817hb7w.css';
import '../../css/o/ozfh193gr.css';
import '../../css/c/c5vbbbbnm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><ellipse class="dt6m_drdp"/><ellipse transform="rotate(15 16.933 24.64)" class="qy0j17i9e"/><ellipse transform="scale(-1 1)rotate(15 -109.047 -105.16)" class="vf817hb7w"/><path class="ozfh193gr"/><path class="c5vbbbbnm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:panda" /></template>
