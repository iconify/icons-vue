<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ofts-6g4o.css';
import '../../css/n/nlascy4eu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ofts-6g4o"/><path class="nlascy4eu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:terminal-square-20" /></template>
