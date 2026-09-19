<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/cuyn6tgcc.css';
import '../../css/d/dejwuwb6s.css';
import '../../css/a/a3u2useig.css';
import '../../css/p/p_yrccbjb.css';
import '../../css/d/d6zxgccaz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#healthiconsRdtResultNoTestNegative0)" class="cuyn6tgcc"><path class="dejwuwb6s"/><path clip-rule="evenodd" class="a3u2useig"/><path clip-rule="evenodd" class="p_yrccbjb"/></g><defs><clipPath id="healthiconsRdtResultNoTestNegative0"><path class="d6zxgccaz"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:rdt-result-no-test-negative" /></template>
