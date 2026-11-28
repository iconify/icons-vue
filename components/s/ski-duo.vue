<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vuuxmnbun.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/c/c9l6zdbzc.css';
import '../../css/b/bmmzlnboq.css';
import '../../css/i/ikwrflpbk.css';
import '../../css/b/bfmc13bjr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary vuuxmnbun"/><g class="dt0cm9dhy primary"><path class="c9l6zdbzc"/><path class="bmmzlnboq"/><path class="ikwrflpbk"/><path class="bfmc13bjr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:ski-duo" /></template>
