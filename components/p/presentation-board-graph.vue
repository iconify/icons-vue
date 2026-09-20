<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/in25xxb2m.css';
import '../../css/t/tut9p6mey.css';
import '../../css/j/j0-ahn93p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="in25xxb2m"/><path class="tut9p6mey"/><path class="j0-ahn93p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:presentation-board-graph" /></template>
