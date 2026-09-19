<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/g/g_8l2sbgi.css';
import '../../css/h/h50xhsmuu.css';
import '../../css/a/aw4i6osni.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="cuyn6tgcc"><path class="g_8l2sbgi"/><path class="h50xhsmuu"/><path class="aw4i6osni"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:person-playing-handball" /></template>
