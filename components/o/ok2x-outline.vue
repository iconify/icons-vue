<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/h/hobtoeb-y.css';
import '../../css/i/i5jeaub5q.css';
import '../../css/s/siob3cbvz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="hobtoeb-y"/><path clip-rule="evenodd" class="i5jeaub5q"/><path clip-rule="evenodd" class="siob3cbvz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:ok2x-outline" /></template>
