<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/h/hc3h7-3-t.css';
import '../../css/q/qzc_kdb0n.css';
import '../../css/w/wz8gm4bgl.css';
import '../../css/w/wqb-0n4qk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="hc3h7-3-t"/><path class="qzc_kdb0n wm-s"/><path class="wz8gm4bgl"/><path class="wm-a wqb-0n4qk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:mail-warning-duo" /></template>
