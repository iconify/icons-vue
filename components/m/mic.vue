<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/b/b9gbdlbzx.css';
import '../../css/n/nccnyto5w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":32};
const content = `<g class="cuyn6tgcc"><path class="b9gbdlbzx"/><path class="nccnyto5w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="et:mic" /></template>
