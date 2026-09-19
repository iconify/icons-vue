<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/geju8gabu.css';
import '../../css/h/hit3bi0-v.css';
import '../../css/j/j-npdpb0r.css';
import '../../css/w/w-gz11o7m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><path id="SVGTYbpMega" class="geju8gabu"/></defs><g class="hit3bi0-v"><use href="#SVGTYbpMega" clip-rule="evenodd"/><use href="#SVGTYbpMega" class="j-npdpb0r"/><path class="w-gz11o7m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:up-c" /></template>
