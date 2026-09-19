<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/j/jfkjynb6a.css';
import '../../css/s/s55ofxbqw.css';
import '../../css/r/rvqiwkblr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="jfkjynb6a"/><path class="s55ofxbqw"/><path class="rvqiwkblr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:toggle-1-duo" /></template>
