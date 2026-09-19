<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/q/qojb79vkl.css';
import '../../css/p/p3-bwf-tg.css';
import '../../css/y/ycfdc-bvw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="qojb79vkl"/><path class="p3-bwf-tg"/><path clip-rule="evenodd" class="ycfdc-bvw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:tablet" /></template>
