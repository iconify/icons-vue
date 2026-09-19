<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ykp9hft_w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ykp9hft_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:minimize-stroke-16" /></template>
