<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/nwr_dwg1v.css';
import '../../css/i/ij4jxkbjm.css';
import '../../css/e/eui6ubbnm.css';
import '../../css/j/jg_dtjh4j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="nwr_dwg1v"/><path class="ij4jxkbjm"/><path class="eui6ubbnm"/><path class="jg_dtjh4j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:sort-numeric-up" /></template>
