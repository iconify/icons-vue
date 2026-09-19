<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/u/ul8qrig3v.css';
import '../../css/p/ph3hdab0i.css';
import '../../css/w/wa65fi0wq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="ul8qrig3v"/><path clip-rule="evenodd" class="ph3hdab0i"/><path class="wa65fi0wq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:rdt-result-pv" /></template>
