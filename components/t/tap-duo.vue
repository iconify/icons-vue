<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/groz-i3ub.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/t/t0-xzacyx.css';
import '../../css/i/i6whcnmcj.css';
import '../../css/x/xczcw10qs.css';
import '../../css/w/we4rjob8q.css';
import '../../css/h/h-g8yzq_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="groz-i3ub secondary"/><g class="dt0cm9dhy primary"><path class="t0-xzacyx"/><path class="i6whcnmcj"/><path class="xczcw10qs"/><path class="we4rjob8q"/><path class="h-g8yzq_q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:tap-duo" /></template>
