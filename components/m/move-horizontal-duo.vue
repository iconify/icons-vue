<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/b/b4eqebb1f.css';
import '../../css/o/omhuwgbnv.css';
import '../../css/t/tk3xwsbbh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="b4eqebb1f"/><path class="omhuwgbnv"/><path class="tk3xwsbbh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:move-horizontal-duo" /></template>
