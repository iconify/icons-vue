<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c608p5bko.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="c608p5bko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:metro" /></template>
