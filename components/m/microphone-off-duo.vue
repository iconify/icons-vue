<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/f/f59prcc4l.css';
import '../../css/q/qr4ochb5c.css';
import '../../css/g/gfjheqbit.css';
import '../../css/w/wsynvg5ce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="f59prcc4l"/><path class="qr4ochb5c wm-s"/><path class="gfjheqbit"/><path class="wm-a wsynvg5ce"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:microphone-off-duo" /></template>
