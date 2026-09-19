<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/d/dduv23k4k.css';
import '../../css/l/l_39joa3l.css';
import '../../css/e/egij13u6h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="dduv23k4k"/><path class="l_39joa3l"/><path class="egij13u6h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:toggles2" /></template>
