<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q816ekbvo.css';
import '../../css/j/j8yh1x58g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="q816ekbvo"/><path class="j8yh1x58g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:pcn-z-node" /></template>
