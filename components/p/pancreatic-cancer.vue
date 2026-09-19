<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/d/di8wmackh.css';
import '../../css/r/r1625-bnw.css';
import '../../css/j/j4wy0zbwb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="di8wmackh"/><path class="r1625-bnw"/><path clip-rule="evenodd" class="j4wy0zbwb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:pancreatic-cancer" /></template>
