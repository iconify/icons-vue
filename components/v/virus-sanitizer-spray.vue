<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/t/t08lfbbqm.css';
import '../../css/f/fttg634dd.css';
import '../../css/g/g6jaddcnb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="t08lfbbqm"/><path class="fttg634dd"/><path class="g6jaddcnb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:virus-sanitizer-spray" /></template>
