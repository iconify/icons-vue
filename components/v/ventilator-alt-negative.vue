<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/cuyn6tgcc.css';
import '../../css/c/c2-cn9vmi.css';
import '../../css/t/tns0z8b5l.css';
import '../../css/d/d6zxgccaz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#healthiconsVentilatorAltNegative0)" class="cuyn6tgcc"><path class="c2-cn9vmi"/><path clip-rule="evenodd" class="tns0z8b5l"/></g><defs><clipPath id="healthiconsVentilatorAltNegative0"><path class="d6zxgccaz"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:ventilator-alt-negative" /></template>
