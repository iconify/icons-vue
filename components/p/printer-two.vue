<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o93lq-byo.css';
import '../../css/l/l6qnrtb2h.css';
import '../../css/o/o39sc1brf.css';
import '../../css/f/fuxnvvbtt.css';
import '../../css/d/ddq83ybsi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="o93lq-byo"><path class="l6qnrtb2h"/><rect class="o39sc1brf"/><path class="fuxnvvbtt"/><path class="ddq83ybsi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:printer-two" /></template>
