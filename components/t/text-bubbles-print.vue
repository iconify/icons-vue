<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/a/agn20jbrn.css';
import '../../css/r/r463ldb8d.css';
import '../../css/r/r5hdsivjz.css';
import '../../css/c/cz98s8cxn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="agn20jbrn"/><path class="r463ldb8d"/><path class="r5hdsivjz"/><path class="cz98s8cxn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:text-bubbles-print" /></template>
