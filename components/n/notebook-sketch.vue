<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/f/f25k-k9hf.css';
import '../../css/q/qy8smfuzj.css';
import '../../css/j/jjk3p5bnj.css';
import '../../css/y/yzld8fb9w.css';
import '../../css/o/o5cn7ub4l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="f25k-k9hf"/><path class="qy8smfuzj wm-k"/><path class="jjk3p5bnj wm-k"/><path class="wm-a yzld8fb9w"/><path class="o5cn7ub4l wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:notebook-sketch" /></template>
