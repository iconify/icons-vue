<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h01tyzbfu.css';
import '../../css/a/aqce0abzy.css';
import '../../css/u/uc71xy3ii.css';
import '../../css/t/td0om22as.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<g class="h01tyzbfu"><circle class="aqce0abzy"/><circle class="uc71xy3ii"/><path class="td0om22as"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:user-group-stroke-12" /></template>
