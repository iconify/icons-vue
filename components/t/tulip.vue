<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/t/t_p5cq_2x.css';
import '../../css/j/jyb22ccqr.css';
import '../../css/s/szjh0obrc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="t_p5cq_2x"/><path class="jyb22ccqr"/><path class="szjh0obrc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:tulip" /></template>
