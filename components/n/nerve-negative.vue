<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/cuyn6tgcc.css';
import '../../css/d/d00t91las.css';
import '../../css/n/n5e0dyi8x.css';
import '../../css/d/d6zxgccaz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#healthiconsNerveNegative0)" class="cuyn6tgcc"><path class="d00t91las"/><path clip-rule="evenodd" class="n5e0dyi8x"/></g><defs><clipPath id="healthiconsNerveNegative0"><path class="d6zxgccaz"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:nerve-negative" /></template>
