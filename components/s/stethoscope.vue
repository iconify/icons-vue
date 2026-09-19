<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/u/u1qtw7b2b.css';
import '../../css/u/u6t9lrs4u.css';
import '../../css/q/qqpblxf5z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="u1qtw7b2b"/><path class="u6t9lrs4u"/><path class="qqpblxf5z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:stethoscope" /></template>
