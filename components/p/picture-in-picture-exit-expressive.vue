<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/c/cyjs5fbfr.css';
import '../../css/f/fv_iub2kb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="cyjs5fbfr"/><path clip-rule="evenodd" class="fv_iub2kb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:picture-in-picture-exit-expressive" /></template>
