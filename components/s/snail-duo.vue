<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ru7ll1byh.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/j/jwr-ufcpq.css';
import '../../css/a/ay1-hpebq.css';
import '../../css/o/olwkaeqqd.css';
import '../../css/o/o-q7-kbqh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ru7ll1byh secondary"/><g class="dt0cm9dhy primary"><path class="jwr-ufcpq"/><path class="ay1-hpebq"/><path class="olwkaeqqd"/><path class="o-q7-kbqh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:snail-duo" /></template>
