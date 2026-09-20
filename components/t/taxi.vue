<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/r/r_f1gcy3d.css';
import '../../css/t/tnjkjq1ws.css';
import '../../css/f/fvvslcb2i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="r_f1gcy3d"/><path class="tnjkjq1ws"/><path class="fvvslcb2i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-print:taxi" /></template>
