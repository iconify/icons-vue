<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/c/c6b32lbva.css';
import '../../css/h/hkw5s0b0y.css';
import '../../css/t/tb7h92xrz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="c6b32lbva"/><path class="hkw5s0b0y"/><path class="tb7h92xrz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:school" /></template>
