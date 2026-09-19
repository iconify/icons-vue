<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/d/da_5j4bpz.css';
import '../../css/v/vm1b4_bnl.css';
import '../../css/o/o6ry9g4ed.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="da_5j4bpz"/><path class="vm1b4_bnl"/><path class="o6ry9g4ed"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:reverse-lens" /></template>
