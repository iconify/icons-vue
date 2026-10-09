<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zwdj28vql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zwdj28vql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:uv-index-48-bold" /></template>
