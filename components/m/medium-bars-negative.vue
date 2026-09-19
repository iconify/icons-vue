<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/cuyn6tgcc.css';
import '../../css/s/s1a2yab2r.css';
import '../../css/g/g4jfx9s0y.css';
import '../../css/d/d6zxgccaz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#healthiconsMediumBarsNegative0)" class="cuyn6tgcc"><path class="s1a2yab2r"/><path clip-rule="evenodd" class="g4jfx9s0y"/></g><defs><clipPath id="healthiconsMediumBarsNegative0"><path class="d6zxgccaz"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:medium-bars-negative" /></template>
