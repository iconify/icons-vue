<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/b/bgbypwxxy.css';
import '../../css/m/mavie6bka.css';
import '../../css/e/e5vcnnbbh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="bgbypwxxy"/><path clip-rule="evenodd" class="mavie6bka"/><path class="e5vcnnbbh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-print:music-note-double" /></template>
