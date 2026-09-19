<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/g/g8yasem6x.css';
import '../../css/k/k-484nzfv.css';
import '../../css/d/doxm9ybid.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="g8yasem6x"/><path class="k-484nzfv"/><path clip-rule="evenodd" class="doxm9ybid"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:sweating2x-outline" /></template>
