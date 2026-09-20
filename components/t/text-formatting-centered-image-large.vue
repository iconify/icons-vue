<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v0xwz2w_y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="v0xwz2w_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:text-formatting-centered-image-large" /></template>
