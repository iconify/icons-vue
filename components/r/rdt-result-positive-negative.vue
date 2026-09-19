<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/cuyn6tgcc.css';
import '../../css/r/r8f7u0bby.css';
import '../../css/a/amnpvd91d.css';
import '../../css/j/jxt58o6cf.css';
import '../../css/d/d6zxgccaz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#healthiconsRdtResultPositiveNegative0)" class="cuyn6tgcc"><path class="r8f7u0bby"/><path clip-rule="evenodd" class="amnpvd91d"/><path clip-rule="evenodd" class="jxt58o6cf"/></g><defs><clipPath id="healthiconsRdtResultPositiveNegative0"><path class="d6zxgccaz"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:rdt-result-positive-negative" /></template>
