<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/p/przz147oy.css';
import '../../css/b/b20r58zph.css';
import '../../css/g/gzee60hjc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="przz147oy"/><path class="b20r58zph"/><path class="gzee60hjc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:spraying" /></template>
