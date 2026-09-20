<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u99l2yxgv.css';
import '../../css/z/z04drlb1l.css';
import '../../css/i/i650vrpib.css';
import '../../css/e/e0rq2fx8z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="u99l2yxgv"/><g class="z04drlb1l"><path class="i650vrpib"/><path class="e0rq2fx8z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:sea-level-rise" /></template>
