<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g95ndgrnv.css';
import '../../css/c/cuyn6tgcc.css';
import '../../css/n/nkc4t8bfx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<defs><path id="SVGpPI6ccam" class="g95ndgrnv"/></defs><mask id="SVGVEeC1biv" class="cuyn6tgcc"><use href="#SVGpPI6ccam"/></mask><g class="cuyn6tgcc"><use href="#SVGpPI6ccam"/><path mask="url(#SVGVEeC1biv)" class="nkc4t8bfx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:panel-bottom" /></template>
