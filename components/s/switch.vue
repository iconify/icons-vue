<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jn8k11clr.css';
import '../../css/g/g_d1rsbwq.css';
import '../../css/d/dcqdxh5zc.css';
import '../../css/y/y-cylzbuw.css';
import '../../css/i/i5q586b1q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="jn8k11clr"/><path class="g_d1rsbwq"/><g class="dcqdxh5zc"><path class="y-cylzbuw"/><path class="i5q586b1q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:switch" /></template>
