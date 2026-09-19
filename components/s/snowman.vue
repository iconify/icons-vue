<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/f/fkgs8cb4p.css';
import '../../css/l/lyesv9buc.css';
import '../../css/t/t_b2msbub.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="cuyn6tgcc"><path class="fkgs8cb4p"/><path class="lyesv9buc"/><path class="t_b2msbub"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:snowman" /></template>
