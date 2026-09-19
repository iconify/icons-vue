<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/lva0ikbbf.css';
import '../../css/q/qceb8-waz.css';
import '../../css/p/pmbl1abpf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="lva0ikbbf"/><path class="qceb8-waz"/><path clip-rule="evenodd" class="pmbl1abpf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:medicines" /></template>
