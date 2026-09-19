<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/fnbjpsbvr.css';
import '../../css/u/uhoxfmboe.css';
import '../../css/q/qpa21bbij.css';
import '../../css/m/mm0rrvbhg.css';
import '../../css/t/tsquhwb9j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="fnbjpsbvr"/><path class="uhoxfmboe"/><path class="qpa21bbij"/><path class="mm0rrvbhg"/><path class="tsquhwb9j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:monkey-face" /></template>
