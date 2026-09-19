<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y5cg8fb9r.css';
import '../../css/y/yo05b4clt.css';
import '../../css/t/tj_b4ycac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y5cg8fb9r"><path class="yo05b4clt"/><path class="tj_b4ycac"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:torch" /></template>
