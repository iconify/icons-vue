<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/r/r38j0dpyp.css';
import '../../css/p/pa5m5tyoc.css';
import '../../css/w/w1pmvsbho.css';
import '../../css/m/muzvyrzzs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="r38j0dpyp"/><path class="pa5m5tyoc"/><path class="w1pmvsbho"/><path class="muzvyrzzs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:signpost" /></template>
