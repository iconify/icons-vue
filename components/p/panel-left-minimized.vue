<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iqr06mblf.css';
import '../../css/c/cuyn6tgcc.css';
import '../../css/c/cvba9qpke.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<defs><path id="SVGr9eWYbHE" class="iqr06mblf"/></defs><mask id="SVGvH4ZXd9x" class="cuyn6tgcc"><use href="#SVGr9eWYbHE"/></mask><g class="cuyn6tgcc"><use href="#SVGr9eWYbHE"/><path mask="url(#SVGvH4ZXd9x)" class="cvba9qpke"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:panel-left-minimized" /></template>
