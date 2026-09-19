<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/g/glhe7bguv.css';
import '../../css/l/ll9vxuj4s.css';
import '../../css/j/jmhfz6b1g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="cuyn6tgcc"><path class="glhe7bguv"/><path class="ll9vxuj4s"/><path class="jmhfz6b1g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:woman-mountain-biking" /></template>
