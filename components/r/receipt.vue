<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/m/mh56y2inu.css';
import '../../css/a/a-1uicclk.css';
import '../../css/h/hf53x_ydx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="mh56y2inu"/><path class="a-1uicclk"/><path class="hf53x_ydx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:receipt" /></template>
