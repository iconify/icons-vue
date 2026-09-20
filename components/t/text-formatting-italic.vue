<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nj5zhkbvl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="nj5zhkbvl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:text-formatting-italic" /></template>
