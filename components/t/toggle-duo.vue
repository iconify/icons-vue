<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/z/z19unwb7b.css';
import '../../css/e/e32c4qbbt.css';
import '../../css/u/u-jiawfxg.css';
import '../../css/d/d90c-y1wv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="z19unwb7b"/><path class="e32c4qbbt"/><path class="u-jiawfxg"/><path class="d90c-y1wv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:toggle-duo" /></template>
