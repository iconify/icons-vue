<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/w/w7987kb8i.css';
import '../../css/f/fl3cbbb-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="w7987kb8i"/><path clip-rule="evenodd" class="fl3cbbb-h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:repo-force-push" /></template>
