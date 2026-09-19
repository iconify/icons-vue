<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/r/rm40z8n3v.css';
import '../../css/j/j0s5_rbqo.css';
import '../../css/p/pv_i1jaoc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="rm40z8n3v"/><path clip-rule="evenodd" class="j0s5_rbqo"/><path clip-rule="evenodd" class="pv_i1jaoc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:photo-camera-print" /></template>
