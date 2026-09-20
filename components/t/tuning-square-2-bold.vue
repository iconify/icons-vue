<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/y/yubpi9bqf.css';
import '../../css/j/jkbq94bnk.css';
import '../../css/h/hufk8dbrf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="yubpi9bqf"/><path class="jkbq94bnk"/><path clip-rule="evenodd" class="hufk8dbrf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:tuning-square-2-bold" /></template>
