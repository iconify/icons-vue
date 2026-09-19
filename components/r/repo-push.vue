<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/z/z4nbeuj_m.css';
import '../../css/q/ql3hqacfh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="z4nbeuj_m"/><path clip-rule="evenodd" class="ql3hqacfh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:repo-push" /></template>
