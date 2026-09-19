<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c2rg35bug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="c2rg35bug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:snowflake" /></template>
