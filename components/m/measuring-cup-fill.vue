<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o0f9isvkl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="o0f9isvkl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:measuring-cup-fill" /></template>
