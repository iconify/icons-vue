<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/y/ya8v8tb_k.css';
import '../../css/p/p1ys4ub_t.css';
import '../../css/n/njw1v7spu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="ya8v8tb_k"/><path class="p1ys4ub_t"/><path class="njw1v7spu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:wifi" /></template>
