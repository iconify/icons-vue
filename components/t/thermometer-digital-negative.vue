<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/rnct339so.css';
import '../../css/d/d6zxgccaz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#healthiconsThermometerDigitalNegative0)"><path clip-rule="evenodd" class="rnct339so"/></g><defs><clipPath id="healthiconsThermometerDigitalNegative0"><path class="d6zxgccaz"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:thermometer-digital-negative" /></template>
