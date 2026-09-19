<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/ir6g6mb-h.css';
import '../../css/p/p0dbfhb3v.css';
import '../../css/m/mltui_b5w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="cuyn6tgcc"><path class="ir6g6mb-h"/><path class="p0dbfhb3v"/><path class="mltui_b5w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:spaghetti" /></template>
