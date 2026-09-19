<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dihsqs3sw.css';
import '../../css/o/o69vp97da.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="dihsqs3sw"/><path class="o69vp97da"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:type-pattern" /></template>
