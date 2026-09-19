<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/l94p16b8n.css';
import '../../css/p/pdn-wtbcg.css';
import '../../css/q/qypm1abiv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="l94p16b8n"/><path class="pdn-wtbcg"/><path class="qypm1abiv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:zoom-out" /></template>
