<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k88a7yboy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="k88a7yboy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:report-outline" /></template>
