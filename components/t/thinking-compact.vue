<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/c/cwtx3g--b.css';
import '../../css/x/xzq_ns0ra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<g class="cuyn6tgcc"><path class="cwtx3g--b"/><path clip-rule="evenodd" class="xzq_ns0ra"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:thinking-compact" /></template>
