<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/j/jz4qbpbes.css';
import '../../css/o/otbkqlb6h.css';
import '../../css/h/hxogdab1a.css';
import '../../css/k/kayfskbga.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="jz4qbpbes"/><path class="otbkqlb6h"/><path class="hxogdab1a"/><path class="kayfskbga"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:robot-head-outline" /></template>
