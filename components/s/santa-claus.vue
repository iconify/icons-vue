<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/e/ew36xlbmo.css';
import '../../css/d/dk5h7lbfd.css';
import '../../css/l/lgvo6lbhk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="cuyn6tgcc"><path class="ew36xlbmo"/><path class="dk5h7lbfd"/><path class="lgvo6lbhk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:santa-claus" /></template>
