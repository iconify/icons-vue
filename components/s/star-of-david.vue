<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/b/bkntsabjl.css';
import '../../css/s/si3vjzbss.css';
import '../../css/w/w2qia4l8w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="bkntsabjl"/><path class="si3vjzbss"/><path clip-rule="evenodd" class="w2qia4l8w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:star-of-david" /></template>
