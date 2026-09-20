<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ctrlet0df.css';
import '../../css/c/cuyn6tgcc.css';
import '../../css/u/u_4xy8b8b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<defs><path id="SVGXWFExeZn" class="ctrlet0df"/></defs><mask id="SVGqCX3GcaG" class="cuyn6tgcc"><use href="#SVGXWFExeZn"/></mask><g class="cuyn6tgcc"><use href="#SVGXWFExeZn"/><path mask="url(#SVGqCX3GcaG)" class="u_4xy8b8b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:panel-right" /></template>
