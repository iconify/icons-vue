<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/p/pfamdko6h.css';
import '../../css/a/a4dm_jfat.css';
import '../../css/j/jpriswb3i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="cuyn6tgcc"><path class="pfamdko6h"/><path class="a4dm_jfat"/><path class="jpriswb3i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:man-running-facing-right" /></template>
