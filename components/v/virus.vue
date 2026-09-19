<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sqg5y4b5p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="sqg5y4b5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:virus" /></template>
