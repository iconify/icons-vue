<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y5cg8fb9r.css';
import '../../css/x/x7-298bge.css';
import '../../css/j/jp5a_pbwx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y5cg8fb9r"><path class="x7-298bge"/><path class="jp5a_pbwx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:treadmill" /></template>
