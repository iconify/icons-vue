<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/g/gtfdr7bxo.css';
import '../../css/b/b19dnacrf.css';
import '../../css/n/nef4w_xbd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="gtfdr7bxo"/><path class="b19dnacrf"/><path class="nef4w_xbd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:times-print" /></template>
