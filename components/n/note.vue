<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/r/ru3n1acww.css';
import '../../css/l/lgzmhqtyx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="s9cl3zbei"><rect class="ru3n1acww"/><path class="lgzmhqtyx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:note" /></template>
