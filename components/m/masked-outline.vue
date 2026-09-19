<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/f/fjv3yr_cl.css';
import '../../css/e/e_m9s3bio.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="fjv3yr_cl"/><path clip-rule="evenodd" class="e_m9s3bio"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:masked-outline" /></template>
