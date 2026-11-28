<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s4jyb4bnk.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/l/lk2gmgbqk.css';
import '../../css/k/kjcpq4b4w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s4jyb4bnk secondary"/><g class="dt0cm9dhy primary"><path class="lk2gmgbqk"/><path class="kjcpq4b4w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:square-play-duo" /></template>
