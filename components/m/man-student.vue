<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/r/r45y58qaa.css';
import '../../css/h/hx50hlb9i.css';
import '../../css/p/pkli7zb5m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="cuyn6tgcc"><path class="r45y58qaa"/><path class="hx50hlb9i"/><path class="pkli7zb5m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:man-student" /></template>
