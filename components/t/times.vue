<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/x/xmm6hwnnj.css';
import '../../css/f/f3w3pwb2i.css';
import '../../css/o/oqsqdyb9y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="xmm6hwnnj"/><path class="f3w3pwb2i"/><path class="oqsqdyb9y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-print:times" /></template>
