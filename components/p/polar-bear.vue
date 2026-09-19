<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/n/ne2ohjbtv.css';
import '../../css/t/tb25r3blk.css';
import '../../css/g/g7z6zobjr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="cuyn6tgcc"><path class="ne2ohjbtv"/><path class="tb25r3blk"/><path class="g7z6zobjr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:polar-bear" /></template>
