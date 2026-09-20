<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/h/hiqwxob7b.css';
import '../../css/u/uxddagbff.css';
import '../../css/p/p-tl4pbfr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="hiqwxob7b"/><path class="uxddagbff"/><path class="p-tl4pbfr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:round-graph-bold-duotone" /></template>
