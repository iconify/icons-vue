<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/z/zhb0pva1h.css';
import '../../css/z/zbbn00bvs.css';
import '../../css/t/tu918tbrk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="zhb0pva1h"/><path class="zbbn00bvs"/><path clip-rule="evenodd" class="tu918tbrk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:select-window" /></template>
