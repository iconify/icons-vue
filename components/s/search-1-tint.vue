<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/k3by9y91o.css';
import '../../css/p/pdn-wtbcg.css';
import '../../css/b/bdnkignkv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="k3by9y91o"/><path class="pdn-wtbcg"/><path class="bdnkignkv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:search-1-tint" /></template>
