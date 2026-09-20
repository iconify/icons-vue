<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wy19rebyk.css';
import '../../css/n/n1mjunbsu.css';
import '../../css/j/j8gr-osck.css';
import '../../css/d/dcqdxh5zc.css';
import '../../css/j/j-npdpb0r.css';
import '../../css/u/ur9ub8kkl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<defs><path id="SVGCHgwedXR" class="wy19rebyk"/></defs><g class="n1mjunbsu"><path class="j8gr-osck"/><use href="#SVGCHgwedXR"/></g><g class="dcqdxh5zc"><use href="#SVGCHgwedXR" class="j-npdpb0r"/><path class="ur9ub8kkl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:white-flag" /></template>
