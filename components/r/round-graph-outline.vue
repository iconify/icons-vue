<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/a/axm7mdb8n.css';
import '../../css/u/uxddagbff.css';
import '../../css/p/p-tl4pbfr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="axm7mdb8n"/><path class="uxddagbff"/><path class="p-tl4pbfr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:round-graph-outline" /></template>
