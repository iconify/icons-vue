<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wkb5n6jyi.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/j/j2vbli9go.css';
import '../../css/w/wgr0qgbwv.css';
import '../../css/l/lm4pd1bxp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary wkb5n6jyi"/><g class="dt0cm9dhy primary"><path class="j2vbli9go"/><path class="wgr0qgbwv"/><path class="lm4pd1bxp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:shield-search-duo" /></template>
