<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/t/ttod6dbvm.css';
import '../../css/h/hi_ztfptr.css';
import '../../css/r/rnunjybvs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="ttod6dbvm"/><path class="hi_ztfptr"/><path clip-rule="evenodd" class="rnunjybvs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:windsock" /></template>
