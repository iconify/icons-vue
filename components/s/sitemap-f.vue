<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/y/yda1e5bll.css';
import '../../css/p/poozqqe-x.css';
import '../../css/d/dle3e5bxo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-1.5};
const content = `<g class="cuyn6tgcc"><path class="yda1e5bll"/><path class="poozqqe-x"/><path class="dle3e5bxo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:sitemap-f" /></template>
