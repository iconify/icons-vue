<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/cuyn6tgcc.css';
import '../../css/y/yey-7bbgd.css';
import '../../css/m/m3w28gbtg.css';
import '../../css/d/d6zxgccaz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#healthiconsPpeMaskNegative0)" class="cuyn6tgcc"><path class="yey-7bbgd"/><path clip-rule="evenodd" class="m3w28gbtg"/></g><defs><clipPath id="healthiconsPpeMaskNegative0"><path class="d6zxgccaz"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:mask-negative" /></template>
