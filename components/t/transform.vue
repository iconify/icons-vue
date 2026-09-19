<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/b/bg65hobfr.css';
import '../../css/d/dq_8uac5l.css';
import '../../css/h/h77qjobjk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><circle class="bg65hobfr"/><circle class="dq_8uac5l"/><path class="h77qjobjk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:transform" /></template>
