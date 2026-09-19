<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i-ye4wb-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="i-ye4wb-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:squares-plus" /></template>
