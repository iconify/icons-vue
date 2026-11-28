<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i_ni2-b3j.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/g/gjhv5h2xq.css';
import '../../css/c/c55ku496r.css';
import '../../css/s/scjaohbsy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i_ni2-b3j secondary"/><g class="dt0cm9dhy primary"><path class="gjhv5h2xq"/><path class="c55ku496r"/><path class="scjaohbsy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:redo-dot-duo" /></template>
