<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/v/ve3z1lb2g.css';
import '../../css/l/lxg7su77s.css';
import '../../css/p/p3mukqotj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="ve3z1lb2g"/><path clip-rule="evenodd" class="lxg7su77s"/><path class="p3mukqotj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:race-car-bold" /></template>
