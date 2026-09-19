<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/d/df5lb0bfh.css';
import '../../css/d/d6zxgccaz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#healthiconsRdtResultNegInvalidRectangularNegative0)"><path clip-rule="evenodd" class="df5lb0bfh"/></g><defs><clipPath id="healthiconsRdtResultNegInvalidRectangularNegative0"><path class="d6zxgccaz"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:rdt-result-neg-invalid-rectangular-negative" /></template>
