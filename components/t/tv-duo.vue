<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/k/kih6jmt2f.css';
import '../../css/v/vug_rebuj.css';
import '../../css/q/qy2dwvndc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="kih6jmt2f"/><path class="vug_rebuj wm-a"/><path class="qy2dwvndc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:tv-duo" /></template>
