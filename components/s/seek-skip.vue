<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ctmlb8_7m.css';
import '../../css/o/ohca03fbp.css';
import '../../css/c/cy8-8obke.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ctmlb8_7m"><path class="ohca03fbp"/><path class="cy8-8obke"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:seek-skip" /></template>
