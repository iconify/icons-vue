<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/h/hxiugsb0s.css';
import '../../css/z/zd3tqrdvm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="hxiugsb0s"/><path class="zd3tqrdvm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:outbreak-outline" /></template>
