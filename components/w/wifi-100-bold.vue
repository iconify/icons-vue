<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xn_x9rbog.css';
import '../../css/c/cuyn6tgcc.css';
import '../../css/y/yygk5x3fo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<defs><path id="SVGBitEHdeU" class="xn_x9rbog"/></defs><g class="cuyn6tgcc"><use href="#SVGBitEHdeU"/><path clip-rule="evenodd" class="yygk5x3fo"/><use href="#SVGBitEHdeU"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:wifi-100-bold" /></template>
