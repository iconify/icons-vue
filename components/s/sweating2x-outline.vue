<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/y/yi_7vme2b.css';
import '../../css/w/w3a9vb0vh.css';
import '../../css/g/gvtuoyesg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="yi_7vme2b"/><path class="w3a9vb0vh"/><path clip-rule="evenodd" class="gvtuoyesg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:sweating2x-outline" /></template>
