<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/c-3yxwbvg.css';
import '../../css/f/f0l3_nh-t.css';
import '../../css/y/ybenv9bfs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="c-3yxwbvg"/><path class="f0l3_nh-t"/><path class="ybenv9bfs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:shopping-bags-duo" /></template>
