<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/y/y8eoimbpp.css';
import '../../css/f/fycg7vbuo.css';
import '../../css/d/d4u2wrb4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="y8eoimbpp"/><path clip-rule="evenodd" class="fycg7vbuo"/><circle class="d4u2wrb4d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:planet-moon" /></template>
