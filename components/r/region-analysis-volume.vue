<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fcnawdb5g.css';
import '../../css/g/gvynxsbvn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fcnawdb5g"/><path class="gvynxsbvn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:region-analysis-volume" /></template>
