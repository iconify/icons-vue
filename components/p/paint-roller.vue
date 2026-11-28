<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/x/x6-qk2bjk.css';
import '../../css/b/biix0ugvx.css';
import '../../css/c/coc26zbtk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="x6-qk2bjk"/><path class="biix0ugvx"/><path class="coc26zbtk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:paint-roller" /></template>
