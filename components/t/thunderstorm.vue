<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j1alc3bdk.css';
import '../../css/b/be9_6yqgb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="j1alc3bdk"/><path class="be9_6yqgb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:thunderstorm" /></template>
