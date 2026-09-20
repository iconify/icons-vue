<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/e/e3b8tiyzr.css';
import '../../css/b/bvtn84bzo.css';
import '../../css/m/mj08r-blc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="e3b8tiyzr"/><path class="bvtn84bzo"/><path class="mj08r-blc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-print:pen" /></template>
