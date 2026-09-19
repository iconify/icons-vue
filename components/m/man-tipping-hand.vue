<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d3pnzib4i.css';
import '../../css/d/dqshecczl.css';
import '../../css/c/c3w9l72hp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="d3pnzib4i"/><path class="dqshecczl"/><path class="c3w9l72hp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:man-tipping-hand" /></template>
