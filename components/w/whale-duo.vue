<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hk68w-bzg.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/x/xw77b1bve.css';
import '../../css/l/lmy0--z2j.css';
import '../../css/c/c63inrb1x.css';
import '../../css/j/j_q0hoqsx.css';
import '../../css/u/uo51fob2t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hk68w-bzg secondary"/><g class="dt0cm9dhy primary"><path class="xw77b1bve"/><path class="lmy0--z2j"/><path class="c63inrb1x"/><path class="j_q0hoqsx"/><path class="uo51fob2t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:whale-duo" /></template>
