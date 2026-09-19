<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/x/x6scb8b-g.css';
import '../../css/j/j5zg0bc7u.css';
import '../../css/o/ocihuquga.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="x6scb8b-g"/><path class="j5zg0bc7u"/><path class="ocihuquga"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:toggle-1-bold" /></template>
