<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pr52f_b5y.css';
import '../../css/z/z4j9yhbxy.css';
import '../../css/f/f1r1xofwi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="pr52f_b5y"><path class="z4j9yhbxy"/><path class="f1r1xofwi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:star-half-1" /></template>
