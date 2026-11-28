<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qpdgzbbxg.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/f/fth_5tbmd.css';
import '../../css/x/xqquot5tz.css';
import '../../css/f/f845xlleg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qpdgzbbxg secondary"/><g class="dt0cm9dhy primary"><path class="fth_5tbmd"/><path class="xqquot5tz"/><path class="f845xlleg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:planet-duo" /></template>
