<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o93lq-byo.css';
import '../../css/l/lwka4hb5s.css';
import '../../css/j/jph5gubwo.css';
import '../../css/b/b62w8-blj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="o93lq-byo"><path class="lwka4hb5s"/><path class="jph5gubwo"/><circle class="b62w8-blj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:seat" /></template>
