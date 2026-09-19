<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/w/wfyy8ibeu.css';
import '../../css/h/h2_n6-bvy.css';
import '../../css/s/sm2rlob0q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="wfyy8ibeu"/><path class="h2_n6-bvy"/><path class="sm2rlob0q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:sim-card-duo" /></template>
