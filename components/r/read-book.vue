<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o93lq-byo.css';
import '../../css/p/pea8xwbap.css';
import '../../css/x/xx2ig22fa.css';
import '../../css/b/b6mu38bbk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="o93lq-byo"><path class="pea8xwbap"/><path class="xx2ig22fa"/><circle class="b6mu38bbk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:read-book" /></template>
