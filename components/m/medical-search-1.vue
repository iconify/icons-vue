<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/d/d6zxgccaz.css';
import '../../css/x/xgd3jb46d.css';
import '../../css/b/bvtg8cc9s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="d6zxgccaz"/><path class="xgd3jb46d"/><path clip-rule="evenodd" class="bvtg8cc9s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:medical-search-1" /></template>
