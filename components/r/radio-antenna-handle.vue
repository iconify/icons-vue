<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kuj8kqcdw.css';
import '../../css/d/d33yrzbil.css';
import '../../css/l/ls49jcb3n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kuj8kqcdw"/><path class="d33yrzbil"/><path class="ls49jcb3n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:radio-antenna-handle" /></template>
