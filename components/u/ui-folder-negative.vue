<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/cuyn6tgcc.css';
import '../../css/o/o-7ayaqiy.css';
import '../../css/w/wl0yr8bgj.css';
import '../../css/d/d6zxgccaz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#healthiconsUiFolderNegative0)" class="cuyn6tgcc"><path class="o-7ayaqiy"/><path clip-rule="evenodd" class="wl0yr8bgj"/></g><defs><clipPath id="healthiconsUiFolderNegative0"><path class="d6zxgccaz"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:ui-folder-negative" /></template>
