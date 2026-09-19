<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/x/x6xhn3kbs.css';
import '../../css/v/va6flgbjg.css';
import '../../css/w/wxs07lbfh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="cuyn6tgcc"><path class="x6xhn3kbs"/><path class="va6flgbjg"/><path class="wxs07lbfh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:waffle" /></template>
