<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/lumpycbom.css';
import '../../css/w/wsr2wubwv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="lumpycbom"/><path clip-rule="evenodd" class="wsr2wubwv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:plane-arrival" /></template>
