<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/q/qfpsajb-o.css';
import '../../css/l/l0tvmr4-e.css';
import '../../css/t/tq2sis96r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><path class="qfpsajb-o"/><path class="l0tvmr4-e"/><path class="tq2sis96r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:webcam" /></template>
