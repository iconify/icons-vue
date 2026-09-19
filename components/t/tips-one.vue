<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gopnm44um.css';
import '../../css/h/hue8_ac7h.css';
import '../../css/d/d2d5prbig.css';
import '../../css/n/nrndtsbfd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="gopnm44um"><path class="hue8_ac7h"/><path class="d2d5prbig"/><path class="nrndtsbfd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:tips-one" /></template>
