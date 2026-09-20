<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/t/tx9t90agw.css';
import '../../css/c/cvmq7ekuv.css';
import '../../css/g/g7qnembxy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="tx9t90agw"/><path class="cvmq7ekuv"/><path class="g7qnembxy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:volume-off" /></template>
