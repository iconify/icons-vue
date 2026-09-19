<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/j/jxr8m2bzo.css';
import '../../css/w/w-ivl6c7l.css';
import '../../css/o/o2u4fe-pd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="jxr8m2bzo"/><path class="w-ivl6c7l"/><path class="o2u4fe-pd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:vertical-timeline" /></template>
