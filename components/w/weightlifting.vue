<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ti4q6eknm.css';
import '../../css/q/qyrg7rbnv.css';
import '../../css/d/dm_j5gglv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ti4q6eknm"><path class="qyrg7rbnv"/><path class="dm_j5gglv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:weightlifting" /></template>
