<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/w/wle43o55h.css';
import '../../css/q/qubz6zaog.css';
import '../../css/d/dmo352x4a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="wle43o55h"/><path class="qubz6zaog"/><path clip-rule="evenodd" class="dmo352x4a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:pediatrics-outline" /></template>
