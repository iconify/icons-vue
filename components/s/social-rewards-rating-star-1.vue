<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f1ttgccey.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="f1ttgccey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:social-rewards-rating-star-1" /></template>
