<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qnkwc0bul.css';
import '../../css/b/bc5-xubfs.css';
import '../../css/s/sk_bn9biv.css';
import '../../css/u/u3l-wgboc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<circle class="qnkwc0bul"/><g class="bc5-xubfs"><circle class="sk_bn9biv"/><path class="u3l-wgboc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:regional-indicator-b" /></template>
