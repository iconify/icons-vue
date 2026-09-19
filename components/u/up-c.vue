<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/g/gz8--lx8p.css';
import '../../css/m/mz340mupd.css';
import '../../css/y/yrx40bbij.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="s9cl3zbei"><path clip-rule="evenodd" class="gz8--lx8p"/><path class="mz340mupd"/><path class="yrx40bbij"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:up-c" /></template>
