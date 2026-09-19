<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/i/i66k2mbcm.css';
import '../../css/z/zqkw5tbxt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="i66k2mbcm"/><path class="zqkw5tbxt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:virus-research" /></template>
