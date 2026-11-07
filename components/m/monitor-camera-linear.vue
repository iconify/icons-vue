<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/u/uz-6ybbfc.css';
import '../../css/p/p0mqq1_8c.css';
import '../../css/k/kva043bzk.css';
import '../../css/j/jt_thrbns.css';
import '../../css/m/m4zupzrqb.css';
import '../../css/w/wqwkkfban.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="uz-6ybbfc"/><path class="p0mqq1_8c"/><path class="kva043bzk"/><path class="jt_thrbns"/><path class="m4zupzrqb"/><path class="wqwkkfban"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:monitor-camera-linear" /></template>
