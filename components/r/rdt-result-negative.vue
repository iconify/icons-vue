<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/cuyn6tgcc.css';
import '../../css/j/j8wxn8xap.css';
import '../../css/u/uol0hcc-e.css';
import '../../css/p/pjln1rbyq.css';
import '../../css/d/d6zxgccaz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#healthiconsRdtResultNegative0)" class="cuyn6tgcc"><path class="j8wxn8xap"/><path clip-rule="evenodd" class="uol0hcc-e"/><path clip-rule="evenodd" class="pjln1rbyq"/></g><defs><clipPath id="healthiconsRdtResultNegative0"><path class="d6zxgccaz"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:rdt-result-negative" /></template>
