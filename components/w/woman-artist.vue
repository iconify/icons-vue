<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/f/f1c4y6ikk.css';
import '../../css/u/urg7fxngv.css';
import '../../css/t/tb8ekkbrt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="cuyn6tgcc"><path class="f1c4y6ikk"/><path class="urg7fxngv"/><path class="tb8ekkbrt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:woman-artist" /></template>
