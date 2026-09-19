<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/m/m_byc2b8w.css';
import '../../css/k/kt65zhk2w.css';
import '../../css/q/qsc59gbln.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="m_byc2b8w"/><path clip-rule="evenodd" class="kt65zhk2w"/><path class="qsc59gbln"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:walk-supported-outline-24px" /></template>
