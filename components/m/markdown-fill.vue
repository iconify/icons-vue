<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c7fm3yptg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="c7fm3yptg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:markdown-fill" /></template>
