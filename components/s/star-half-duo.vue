<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m08t2fb5l.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/v/vxnjoccwe.css';
import '../../css/u/u_4blpxzy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m08t2fb5l secondary"/><g class="dt0cm9dhy primary"><path class="vxnjoccwe"/><path class="u_4blpxzy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:star-half-duo" /></template>
