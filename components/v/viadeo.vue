<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/a/aly3a1bmz.css';
import '../../css/k/k8x35gqat.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-3,"top":-2};
const content = `<g class="cuyn6tgcc"><path class="aly3a1bmz"/><path class="k8x35gqat"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:viadeo" /></template>
