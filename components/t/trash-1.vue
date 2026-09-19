<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/sup606y1b.css';
import '../../css/b/blcprgz6v.css';
import '../../css/n/nlp7aobgj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="sup606y1b"/><path class="blcprgz6v"/><path class="nlp7aobgj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:trash-1" /></template>
