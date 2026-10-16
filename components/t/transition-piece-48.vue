<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oqrfj76nr.css';
import '../../css/j/j_lztvbdd.css';
import '../../css/p/p3mle5ske.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="oqrfj76nr"/><path class="j_lztvbdd"/><path class="p3mle5ske"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:transition-piece-48" /></template>
