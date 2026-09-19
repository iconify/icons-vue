<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h_11oy1hr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="h_11oy1hr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:rearrange-stroke-16" /></template>
