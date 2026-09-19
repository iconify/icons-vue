<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/irjh9jilq.css';
import '../../css/g/ggd2cgbpw.css';
import '../../css/y/yyrmujbrk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="irjh9jilq"/><path class="ggd2cgbpw"/><path class="yyrmujbrk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:star-and-crescent-bold" /></template>
