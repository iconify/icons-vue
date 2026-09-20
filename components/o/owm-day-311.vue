<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kw6b3sbsa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="kw6b3sbsa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:owm-day-311" /></template>
