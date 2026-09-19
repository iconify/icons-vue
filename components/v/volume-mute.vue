<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/y/yljvlcm9c.css';
import '../../css/m/mi58zrbsp.css';
import '../../css/k/kvf1k6b_t.css';
import '../../css/l/la-lxablh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="yljvlcm9c"/><path class="mi58zrbsp"/><path class="kvf1k6b_t"/><path class="la-lxablh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:volume-mute" /></template>
