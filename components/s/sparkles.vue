<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wwvp95byt.css';
import '../../css/e/e6magr92w.css';
import '../../css/u/ux7a-acay.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="wwvp95byt"><path class="e6magr92w"/><path class="ux7a-acay"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:sparkles" /></template>
