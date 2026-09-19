<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/cuyn6tgcc.css';
import '../../css/u/uqvbbja5z.css';
import '../../css/t/tbm8j2f_f.css';
import '../../css/h/hr8u48_gi.css';
import '../../css/d/d6zxgccaz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#healthiconsNervousNegative0)" class="cuyn6tgcc"><path class="uqvbbja5z"/><path clip-rule="evenodd" class="tbm8j2f_f"/><path clip-rule="evenodd" class="hr8u48_gi"/></g><defs><clipPath id="healthiconsNervousNegative0"><path class="d6zxgccaz"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:nervous-negative" /></template>
