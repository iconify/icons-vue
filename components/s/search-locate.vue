<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dhnrghbie.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="dhnrghbie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:search-locate" /></template>
