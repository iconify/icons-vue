<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/t/t0baxibkh.css';
import '../../css/m/mdjx2zbma.css';
import '../../css/w/w8m--pb8p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="s9cl3zbei"><path clip-rule="evenodd" class="t0baxibkh"/><path class="mdjx2zbma"/><path class="w8m--pb8p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:traditional-chinese-medicine" /></template>
