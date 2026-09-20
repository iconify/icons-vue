<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jgv1q4brx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="jgv1q4brx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:nature-water" /></template>
