<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/its__g-kj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="its__g-kj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:view-list" /></template>
