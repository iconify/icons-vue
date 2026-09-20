<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/f/f2gl3acpc.css';
import '../../css/x/xc0yxgbay.css';
import '../../css/u/udt3hqb4c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="f2gl3acpc"/><path clip-rule="evenodd" class="xc0yxgbay"/><path class="udt3hqb4c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:plug" /></template>
