<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/j/juo2ho41m.css';
import '../../css/y/y-wgo2cte.css';
import '../../css/q/q1b0w0zoz.css';
import '../../css/l/lxqkkqmys.css';
import '../../css/t/td49gbbjb.css';
import '../../css/j/j314kuthn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="juo2ho41m wm-k"/><path class="wm-a y-wgo2cte"/><path class="q1b0w0zoz wm-shadow"/><path class="lxqkkqmys wm-k"/><path class="td49gbbjb wm-k"/><path class="j314kuthn wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:rose-engrave" /></template>
