<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p20d__orr.css';
import '../../css/h/hxy5vm6-q.css';
import '../../css/v/vy_mjj2zg.css';
import '../../css/i/iy5e-0bly.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p20d__orr"/><path class="hxy5vm6-q"/><g id="SVGCwrnbc9w"><path class="vy_mjj2zg"/><path class="iy5e-0bly"/></g><use width="100%" height="100%" href="#SVGCwrnbc9w" transform="matrix(-1 0 0 1 512 0)"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flag:mo-1x1" /></template>
