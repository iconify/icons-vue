<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qfkpbtgle.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":376,"height":400};
const content = `<path class="qfkpbtgle"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:search-replace" /></template>
