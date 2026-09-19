<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xc9b90bna.css';
import '../../css/a/ai5cs6a6e.css';
import '../../css/f/fcjz4bwnd.css';
import '../../css/j/jfdb2j0lk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="xc9b90bna"><path class="ai5cs6a6e"/><ellipse class="fcjz4bwnd"/><path class="jfdb2j0lk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:music-note-bold" /></template>
