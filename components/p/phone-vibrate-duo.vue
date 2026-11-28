<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g8l923lnx.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/w/wlrfrla8c.css';
import '../../css/m/m03d7tfff.css';
import '../../css/h/htwhtdbse.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g8l923lnx secondary"/><g class="dt0cm9dhy primary"><path class="wlrfrla8c"/><path class="m03d7tfff"/><path class="htwhtdbse"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:phone-vibrate-duo" /></template>
