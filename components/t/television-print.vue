<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/p/pgz7pebzt.css';
import '../../css/f/fliydl4-z.css';
import '../../css/o/o4m_-_bfl.css';
import '../../css/m/mn2ysebzg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="pgz7pebzt"/><path clip-rule="evenodd" class="fliydl4-z"/><path class="o4m_-_bfl"/><path class="mn2ysebzg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:television-print" /></template>
