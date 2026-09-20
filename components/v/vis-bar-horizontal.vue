<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jli5rnb2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jli5rnb2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:vis-bar-horizontal" /></template>
