<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/e/ed7n6b7iy.css';
import '../../css/c/c3fqsnlyc.css';
import '../../css/d/dgjqt8bah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="ed7n6b7iy"/><path class="c3fqsnlyc"/><path class="dgjqt8bah"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:uterus" /></template>
