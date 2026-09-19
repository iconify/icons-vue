<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/lo-104boj.css';
import '../../css/a/amdf2k30j.css';
import '../../css/q/qt50d49vp.css';
import '../../css/p/p6fs5dave.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="lo-104boj"/><path class="amdf2k30j"/><path clip-rule="evenodd" class="qt50d49vp"/><path class="p6fs5dave"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:smoking-outline" /></template>
