<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/n1lsf0bnc.css';
import '../../css/y/yxb5jbb2z.css';
import '../../css/z/zs-kct37k.css';
import '../../css/d/d6zxgccaz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#healthiconsOkNegative0)" clip-rule="evenodd" class="n1lsf0bnc"><path class="yxb5jbb2z"/><path class="zs-kct37k"/></g><defs><clipPath id="healthiconsOkNegative0"><path class="d6zxgccaz"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:ok-negative" /></template>
