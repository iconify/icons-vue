<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m_lejeueo.css';
import '../../css/k/kk80kc5ca.css';
import '../../css/i/ij2x_72vy.css';
import '../../css/a/a4t5l_bes.css';
import '../../css/q/qjy-lhbwx.css';
import '../../css/n/n10vw1wtt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="m_lejeueo"/><path class="kk80kc5ca"/><g class="ij2x_72vy"><path class="a4t5l_bes"/><path class="qjy-lhbwx"/><path class="n10vw1wtt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:zebra" /></template>
