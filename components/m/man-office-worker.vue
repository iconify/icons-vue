<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/p/pxsie3b8b.css';
import '../../css/c/cnlsa2f2b.css';
import '../../css/t/ts11t6b7c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="cuyn6tgcc"><path class="pxsie3b8b"/><path class="cnlsa2f2b"/><path class="ts11t6b7c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:man-office-worker" /></template>
