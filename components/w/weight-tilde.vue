<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/h/hn3nmybwz.css';
import '../../css/s/s-527o7ge.css';
import '../../css/w/wmu9zebde.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="hn3nmybwz"/><path class="s-527o7ge"/><path class="wmu9zebde"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:weight-tilde" /></template>
