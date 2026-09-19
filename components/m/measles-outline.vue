<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/u/u99lp1b_s.css';
import '../../css/l/lbb-5lblm.css';
import '../../css/i/iuxtdgbnr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="u99lp1b_s"/><path class="lbb-5lblm"/><path clip-rule="evenodd" class="iuxtdgbnr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:measles-outline" /></template>
