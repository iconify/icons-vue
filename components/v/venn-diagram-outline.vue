<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h01tyzbfu.css';
import '../../css/j/jwvhftb8e.css';
import '../../css/e/e4b5jwbkp.css';
import '../../css/c/cx1-3ebcg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<g class="h01tyzbfu"><path class="jwvhftb8e"/><path class="e4b5jwbkp"/><path class="cx1-3ebcg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:venn-diagram-outline" /></template>
