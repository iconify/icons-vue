<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/pdhw08cew.css';
import '../../css/e/e0gyz35bk.css';
import '../../css/t/tc-tj3qvr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="pdhw08cew"/><path class="e0gyz35bk"/><path class="tc-tj3qvr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:timer-1-duo" /></template>
