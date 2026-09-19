<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zffpzhbdi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zffpzhbdi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:segmented-nav" /></template>
