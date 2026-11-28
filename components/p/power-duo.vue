<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lsjzq4bne.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/r/rb8rwv0pa.css';
import '../../css/p/p38r5q0if.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lsjzq4bne secondary"/><g class="dt0cm9dhy primary"><path class="rb8rwv0pa"/><path class="p38r5q0if"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:power-duo" /></template>
