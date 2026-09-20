<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/e/ecuvllbog.css';
import '../../css/m/m_wrpt7lk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="cuyn6tgcc"><circle class="ecuvllbog"/><path class="m_wrpt7lk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="quill:stack" /></template>
