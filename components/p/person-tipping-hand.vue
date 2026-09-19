<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/r/rw23uxbfk.css';
import '../../css/d/dy1u4_bpm.css';
import '../../css/i/ijbqnrrlq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="cuyn6tgcc"><path class="rw23uxbfk"/><path class="dy1u4_bpm"/><path class="ijbqnrrlq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:person-tipping-hand" /></template>
