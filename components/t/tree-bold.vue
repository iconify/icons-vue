<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/h/h7tub3zqh.css';
import '../../css/r/rza32tfef.css';
import '../../css/k/khe_6c_pj.css';
import '../../css/d/d9-olkb3q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="h7tub3zqh"/><path class="rza32tfef"/><path clip-rule="evenodd" class="khe_6c_pj"/><path class="d9-olkb3q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:tree-bold" /></template>
