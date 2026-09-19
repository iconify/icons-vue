<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/n1lsf0bnc.css';
import '../../css/m/menjzbecp.css';
import '../../css/n/n1d5zjbwq.css';
import '../../css/d/d6zxgccaz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#healthiconsUiZoomInNegative0)" clip-rule="evenodd" class="n1lsf0bnc"><path class="menjzbecp"/><path class="n1d5zjbwq"/></g><defs><clipPath id="healthiconsUiZoomInNegative0"><path class="d6zxgccaz"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:ui-zoom-in-negative" /></template>
