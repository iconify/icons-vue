<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/k/kcytghzxu.css';
import '../../css/p/ppgi3vj8t.css';
import '../../css/o/ozjkdu0on.css';
import '../../css/h/h7focp4gr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="kcytghzxu"/><path class="ppgi3vj8t wm-a"/><path class="ozjkdu0on"/><path class="h7focp4gr wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:webcam-duo" /></template>
