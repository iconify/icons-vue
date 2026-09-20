<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o4c6lqbbt.css';
import '../../css/c/cvtxclbmf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o4c6lqbbt"/><path class="cvtxclbmf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:stats-line-graph-circle" /></template>
