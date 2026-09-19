<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/k/kqfytvbmd.css';
import '../../css/j/jturxcmib.css';
import '../../css/a/awhq7acwr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="kqfytvbmd"/><path class="jturxcmib"/><path clip-rule="evenodd" class="awhq7acwr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:xray2x-outline" /></template>
