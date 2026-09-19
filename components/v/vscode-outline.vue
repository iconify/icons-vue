<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/i/i3snn9big.css';
import '../../css/r/rvihihrlp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="i3snn9big"/><path class="rvihihrlp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:vscode-outline" /></template>
