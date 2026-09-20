<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y3xf5ebcd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="y3xf5ebcd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:text-formatting-top-image" /></template>
