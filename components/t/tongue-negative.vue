<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/cuyn6tgcc.css';
import '../../css/q/qrxwnpbxg.css';
import '../../css/o/owcquwb3a.css';
import '../../css/l/lj_iaub6h.css';
import '../../css/d/d6zxgccaz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#healthiconsTongueNegative0)" class="cuyn6tgcc"><path clip-rule="evenodd" class="qrxwnpbxg"/><path class="owcquwb3a"/><path clip-rule="evenodd" class="lj_iaub6h"/></g><defs><clipPath id="healthiconsTongueNegative0"><path class="d6zxgccaz"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:tongue-negative" /></template>
