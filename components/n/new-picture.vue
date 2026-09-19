<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/x/xhdah4bbl.css';
import '../../css/m/m5atj7b7d.css';
import '../../css/h/hjisqlb_t.css';
import '../../css/w/w7n07nbhl.css';
import '../../css/j/j5l3cjbcg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><rect class="xhdah4bbl"/><path class="m5atj7b7d"/><path class="hjisqlb_t"/><path class="w7n07nbhl"/><path class="j5l3cjbcg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:new-picture" /></template>
