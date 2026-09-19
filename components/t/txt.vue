<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n9cb8g7fg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="n9cb8g7fg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:txt" /></template>
