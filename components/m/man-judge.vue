<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/d/dr4nqvw3k.css';
import '../../css/e/e7ha1tbiu.css';
import '../../css/a/akrz7xbnl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="cuyn6tgcc"><path class="dr4nqvw3k"/><path class="e7ha1tbiu"/><path class="akrz7xbnl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:man-judge" /></template>
