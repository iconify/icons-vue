<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dw1j1ccsi.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/w/wssr8ubfg.css';
import '../../css/m/mrx54rbjt.css';
import '../../css/b/bvxuivbfy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dw1j1ccsi secondary"/><g class="dt0cm9dhy primary"><path class="wssr8ubfg"/><path class="mrx54rbjt"/><path class="bvxuivbfy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:symmetry-vertical-duo" /></template>
