<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/h_5g2hi6q.css';
import '../../css/c/cu16s__pq.css';
import '../../css/v/vm5081bct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="h_5g2hi6q"/><path class="cu16s__pq"/><path clip-rule="evenodd" class="vm5081bct"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:tags" /></template>
