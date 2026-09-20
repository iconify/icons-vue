<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/c/c6y0h7bnk.css';
import '../../css/f/fssqibcht.css';
import '../../css/q/qwt-1fbxl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="c6y0h7bnk"/><path class="fssqibcht"/><path clip-rule="evenodd" class="qwt-1fbxl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:remote2-duotone" /></template>
