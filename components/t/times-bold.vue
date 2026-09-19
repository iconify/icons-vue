<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a__s2g6zp.css';
import '../../css/w/wbf1jl94t.css';
import '../../css/g/gz1qx8bxy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="a__s2g6zp"><path class="wbf1jl94t"/><path class="gz1qx8bxy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:times-bold" /></template>
