<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w4nzv9bqi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="w4nzv9bqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:raindrop" /></template>
