<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/akzm_vtle.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/t/t0f2x9b0h.css';
import '../../css/a/af_7eacyu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="akzm_vtle secondary"/><g class="dt0cm9dhy primary"><path class="t0f2x9b0h"/><path class="af_7eacyu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:message-square-sparkles-duo" /></template>
