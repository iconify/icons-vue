<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/h/hku6jab1q.css';
import '../../css/q/qia370byn.css';
import '../../css/h/hzk5kpusw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="hku6jab1q"/><path class="qia370byn"/><path clip-rule="evenodd" class="hzk5kpusw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:panels-bottom-right-bold" /></template>
