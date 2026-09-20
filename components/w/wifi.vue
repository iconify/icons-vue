<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hcvm4-bpr.css';
import '../../css/m/mdxhb0bme.css';
import '../../css/s/ss0le4b0t.css';
import '../../css/a/aam2fvvmq.css';
import '../../css/j/j9m8ctbnv.css';
import '../../css/i/ij2x_72vy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<defs><path id="SVGl6kMrI8J" class="hcvm4-bpr"/><path id="SVGB29e7djA" class="mdxhb0bme"/><path id="SVG3i9oCczf" class="ss0le4b0t"/></defs><g class="aam2fvvmq"><use href="#SVGl6kMrI8J"/><use href="#SVGB29e7djA"/><use href="#SVG3i9oCczf"/><circle class="j9m8ctbnv"/></g><g class="ij2x_72vy"><use href="#SVGl6kMrI8J"/><use href="#SVGB29e7djA"/><use href="#SVG3i9oCczf"/><circle class="j9m8ctbnv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:wifi" /></template>
