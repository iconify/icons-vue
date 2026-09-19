<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o93lq-byo.css';
import '../../css/s/s-8_facdk.css';
import '../../css/m/m0v40n6wf.css';
import '../../css/d/duzg3-npv.css';
import '../../css/m/m0hl1rncr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="o93lq-byo"><circle class="s-8_facdk"/><path class="m0v40n6wf"/><circle class="duzg3-npv"/><path class="m0hl1rncr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:people-search-one" /></template>
