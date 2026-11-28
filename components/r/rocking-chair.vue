<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/m/mxiihibxh.css';
import '../../css/u/u5egpobzl.css';
import '../../css/w/wmsjuibuj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="mxiihibxh"/><path class="u5egpobzl"/><path class="wmsjuibuj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:rocking-chair" /></template>
