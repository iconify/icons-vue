<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zqp4n6_wf.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/g/g2f38_bgz.css';
import '../../css/x/xgirfrbpu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary zqp4n6_wf"/><g class="dt0cm9dhy primary"><path class="g2f38_bgz"/><path class="xgirfrbpu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:youtube-duo" /></template>
