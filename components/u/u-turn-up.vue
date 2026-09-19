<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/y/yiy1b3n8l.css';
import '../../css/o/o4ouqrbli.css';
import '../../css/x/xy_xzzmno.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="yiy1b3n8l"/><path class="o4ouqrbli"/><circle transform="rotate(-90 13 9)" class="xy_xzzmno"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:u-turn-up" /></template>
