<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zjeg9sbfw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zjeg9sbfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:plug-stroke-16" /></template>
