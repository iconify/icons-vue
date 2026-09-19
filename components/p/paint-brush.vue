<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/e/eu560-7oy.css';
import '../../css/z/z0nhkbcvf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="eu560-7oy"/><path class="z0nhkbcvf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:paint-brush" /></template>
