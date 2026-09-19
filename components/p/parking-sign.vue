<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/u/ue_al4hoa.css';
import '../../css/u/u05je9dcy.css';
import '../../css/i/i8tckab1e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="ue_al4hoa"/><path class="u05je9dcy"/><path class="i8tckab1e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:parking-sign" /></template>
