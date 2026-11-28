<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iercfls4x.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/v/vpr67b4vu.css';
import '../../css/k/kdk4_sbmk.css';
import '../../css/d/d7bxwzrwj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iercfls4x secondary"/><g class="dt0cm9dhy primary"><path class="vpr67b4vu"/><path class="kdk4_sbmk"/><path class="d7bxwzrwj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:music-duo" /></template>
