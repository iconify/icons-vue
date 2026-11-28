<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t5lj33z7x.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/a/ay7v23jbz.css';
import '../../css/l/ltw4lrqoo.css';
import '../../css/a/anx3l54he.css';
import '../../css/a/a6to1-bzk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary t5lj33z7x"/><g class="dt0cm9dhy primary"><path class="ay7v23jbz"/><path class="ltw4lrqoo"/><path class="anx3l54he"/><path class="a6to1-bzk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:scanner-duo" /></template>
