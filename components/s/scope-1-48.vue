<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j0b5pxbkr.css';
import '../../css/j/jtr7gubri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j0b5pxbkr"/><path class="jtr7gubri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:scope-1-48" /></template>
