<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/lum00wbsm.css';
import '../../css/d/d07l4yz5d.css';
import '../../css/b/b-uqsybpr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="lum00wbsm"/><path class="d07l4yz5d"/><path class="b-uqsybpr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:pen-1" /></template>
