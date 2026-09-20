<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/z/zfopdhy3l.css';
import '../../css/c/c984gybxi.css';
import '../../css/u/uwgnrnbkn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="zfopdhy3l"/><path class="c984gybxi"/><path class="uwgnrnbkn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:video-player-slider" /></template>
