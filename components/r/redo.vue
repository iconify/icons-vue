<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/d/dn62s8bnc.css';
import '../../css/i/iv6ig5_zh.css';
import '../../css/z/zszk8c9_v.css';
import '../../css/r/r2hl45bem.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="dn62s8bnc wm-k"/><path class="iv6ig5_zh wm-k"/><path class="wm-k zszk8c9_v"/><path class="r2hl45bem wm-shine"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-anime:redo" /></template>
