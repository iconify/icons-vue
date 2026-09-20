<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d3ed_tbcr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="d3ed_tbcr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:restaurant" /></template>
