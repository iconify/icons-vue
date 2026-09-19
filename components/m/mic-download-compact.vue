<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/u/uxv44pbef.css';
import '../../css/j/jr8aifbqs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="uxv44pbef"/><path class="jr8aifbqs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:mic-download-compact" /></template>
