<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cbngglbom.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/a/atjibysll.css';
import '../../css/h/hbmvtsmai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cbngglbom secondary"/><g class="dt0cm9dhy primary"><path class="atjibysll"/><path class="hbmvtsmai"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:thumbs-up-duo" /></template>
