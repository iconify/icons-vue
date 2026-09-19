<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bs423rb-x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="bs423rb-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:multiline-stroke-16" /></template>
