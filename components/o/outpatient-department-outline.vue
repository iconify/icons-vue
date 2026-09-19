<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/j/jk7rslbwk.css';
import '../../css/s/swdq09oqv.css';
import '../../css/j/jshl0cs6f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="jk7rslbwk"/><path class="swdq09oqv"/><path clip-rule="evenodd" class="jshl0cs6f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:outpatient-department-outline" /></template>
