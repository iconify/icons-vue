<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ap8s5ibrc.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/j/j2vbli9go.css';
import '../../css/c/chkx7cvvy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ap8s5ibrc secondary"/><g class="dt0cm9dhy primary"><path class="j2vbli9go"/><path class="chkx7cvvy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:shield-heart-duo" /></template>
