<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/h/hc6cvzxwd.css';
import '../../css/v/vcbo6ob6i.css';
import '../../css/f/frsup1bzk.css';
import '../../css/h/hchtjubcw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="hc6cvzxwd"/><path class="vcbo6ob6i wm-a"/><path class="frsup1bzk"/><path class="hchtjubcw wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:router-duo" /></template>
