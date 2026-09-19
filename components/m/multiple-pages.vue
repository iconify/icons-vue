<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/c/c9bmclb1d.css';
import '../../css/t/tjswyhbej.css';
import '../../css/n/nje5g0bbx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="c9bmclb1d"/><path class="tjswyhbej"/><path class="nje5g0bbx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:multiple-pages" /></template>
