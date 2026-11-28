<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dq4-99b5e.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/m/mf-b0qbej.css';
import '../../css/u/u2h6v2jyt.css';
import '../../css/i/i3vad_bkp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dq4-99b5e secondary"/><g class="dt0cm9dhy primary"><path class="mf-b0qbej"/><path class="u2h6v2jyt"/><path class="i3vad_bkp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:mars-duo" /></template>
