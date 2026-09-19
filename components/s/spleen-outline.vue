<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/e/eqquj7bkg.css';
import '../../css/g/gi4z11bdi.css';
import '../../css/i/icynqdbqy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="eqquj7bkg"/><path class="gi4z11bdi"/><path class="icynqdbqy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:spleen-outline" /></template>
