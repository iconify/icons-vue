<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yrq4i1bwa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":16};
const content = `<path class="yrq4i1bwa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:sync" /></template>
