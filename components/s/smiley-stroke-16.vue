<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h01tyzbfu.css';
import '../../css/u/urswrcbmq.css';
import '../../css/o/oa4409lwh.css';
import '../../css/c/cuyn6tgcc.css';
import '../../css/f/fw5rt46mg.css';
import '../../css/y/y54gef5lv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="h01tyzbfu"><circle class="urswrcbmq"/><path class="oa4409lwh"/></g><g class="cuyn6tgcc"><circle class="fw5rt46mg"/><circle class="y54gef5lv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:smiley-stroke-16" /></template>
