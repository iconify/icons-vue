<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/lt1f3wyyx.css';
import '../../css/i/ilh-kebmx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="lt1f3wyyx"/><path clip-rule="evenodd" class="ilh-kebmx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:medicine-bottle2x-outline" /></template>
