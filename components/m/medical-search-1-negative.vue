<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/cuyn6tgcc.css';
import '../../css/w/wz617hibg.css';
import '../../css/r/rqa-i6zlt.css';
import '../../css/o/ozpmt6nrj.css';
import '../../css/d/d6zxgccaz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#healthiconsMedicalSearch1Negative0)" class="cuyn6tgcc"><path clip-rule="evenodd" class="wz617hibg"/><path class="rqa-i6zlt"/><path clip-rule="evenodd" class="ozpmt6nrj"/></g><defs><clipPath id="healthiconsMedicalSearch1Negative0"><path class="d6zxgccaz"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:medical-search-1-negative" /></template>
