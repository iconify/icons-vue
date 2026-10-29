<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/d/d2q1tdbbp.css';
import '../../css/m/m3-ef15ju.css';
import '../../css/t/t_jrdsb4n.css';
import '../../css/k/kcbeidzug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="d2q1tdbbp"/><path class="m3-ef15ju wm-a"/><path class="t_jrdsb4n wm-a"/><path class="kcbeidzug"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:pipette-duo" /></template>
