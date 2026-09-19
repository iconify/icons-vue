<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/e/e1cvcgc3f.css';
import '../../css/l/lq-gwm3-q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="e1cvcgc3f"/><path clip-rule="evenodd" class="lq-gwm3-q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:whole-word" /></template>
