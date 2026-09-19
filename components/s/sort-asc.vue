<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yrpqgccob.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1344};
const content = `<path class="yrpqgccob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:sort-asc" /></template>
