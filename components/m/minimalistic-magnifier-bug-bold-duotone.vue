<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/g/gutmv4bns.css';
import '../../css/d/dzwotfb7f.css';
import '../../css/e/em6y05bsv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="gutmv4bns"/><path clip-rule="evenodd" class="dzwotfb7f"/><path class="em6y05bsv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:minimalistic-magnifier-bug-bold-duotone" /></template>
