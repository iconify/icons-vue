<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/j/jceh016qq.css';
import '../../css/m/mvc1e_bil.css';
import '../../css/p/p7iqdlb2g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="jceh016qq"/><path class="mvc1e_bil"/><path class="p7iqdlb2g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:store" /></template>
