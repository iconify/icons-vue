<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g_igsccvz.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/d/diqg_sbxg.css';
import '../../css/e/e11icibaw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g_igsccvz secondary"/><g class="dt0cm9dhy primary"><path class="diqg_sbxg"/><path class="e11icibaw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:pill-duo" /></template>
