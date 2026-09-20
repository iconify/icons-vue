<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ai7m974dg.css';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/lgb4f-pur.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<defs><path id="SVGzlrrcbgz" class="ai7m974dg"/></defs><mask id="SVGoefgPbdu" class="cuyn6tgcc"><use href="#SVGzlrrcbgz"/></mask><g class="cuyn6tgcc"><use href="#SVGzlrrcbgz"/><path mask="url(#SVGoefgPbdu)" class="lgb4f-pur"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:panel-left" /></template>
